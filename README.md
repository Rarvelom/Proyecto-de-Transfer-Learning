# Proyecto-de-Transfer-Learning
Transfer learning project developed as part of the AI ​​bootcamp. We applied fine-tuning techniques to pre-trained models to solve a real-world problem using a small dataset. The goal is to demonstrate how to repurpose existing models to achieve effective results in a short period of time.

# Transfer Learning Project - Art Classifier

This project was developed as part of the Transfer Learning module of an Artificial Intelligence bootcamp. Over the course of three days, our team applied fine-tuning techniques on a pre-trained model to address a specific problem that we are passionate about.

## Project Objective

To develop a Transfer Learning-based model to classify artworks by artistic style using a subset of the WikiArt dataset. The goal is to accurately identify the style of a given painting (e.g., Impressionism, Surrealism, Cubism, etc.) using a dataset and a pre-trained model.
## Motivation

We believe that leveraging pre-trained models democratizes the use of artificial intelligence by enabling complex problem-solving even with limited data. This project allowed us to explore this potential and better understand how to adapt existing models to new tasks in a resource-efficient way, especially in artistic and cultural domains.

## Methodology

1. **Problem and Dataset Selection**
   - Problem: Image classification of artworks by artistic style.
   - Dataset: WikiArt dataset (subset).
   - Number of classes: 10 styles.
   - Approximate samples per class: ~200-300.

2. **Selected Pre-trained Model**
   - Model: MobileNetV2.
   - Source: Tensorflow Hub.

3. **Adaptations and Fine-tuning**
   - Added custom classification layers on top of the base model.
   - Fine-tuned the last few layers of MobileNetV2.
   - Applied data augmentation techniques (rotation, flipping, zooming) to increase robustness and reduce overfitting.
     
## Tools and Technologies

- Python.
- TensorFlow / Keras.
- Google Colab.
- scikit-learn
- Matplotlib / Seaborn for visualizations

## Expected Results

- Validation accuracy: 85%.
- Loss and accuracy curves during training.
- Confusion matrix on validation data.
- Sample prediction results and error analysis.

## Conclusions

- Advantages: Transfer Learning allowed us to obtain high performance with limited data and compute resources.
- Challenges: Class imbalance and visual similarity between styles and overfitting on some classes due to limited data.
- Potential next steps with more time or data:
      - Incorporate more samples or balance the dataset.
      - Explore other architectures.
      - Deploy the model as a web app for public interaction.

## Repository Structure


## 📁 Estructura del repositorio

├── data/ # Training and validation data.

├── notebooks/ # Google Colab.

├── models/ # Fine-tuned model weights (if applicable).

├── src/ # Source code (e.g, preprocessing, model training).

├── README.md # This file.

## 👥 Team

- Ricardo Arvelo Meza [Rarvelom]
- Laura Sanchez Gonzalez [laurasang13]
- Sindy Davila Londoño [Sindy138]


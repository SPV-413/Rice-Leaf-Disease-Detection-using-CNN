# Rice Leaf Disease Detection using CNN
This project implements an image classification model using Convolutional Neural Networks (CNN) to detect rice leaf diseases. The model is trained and evaluated **with and without data augmentation** to compare performance.

## Dataset Description

This dataset contains **120 color (.jpg) images** of disease-infected rice leaves. The images are categorized into **3 classes** based on the type of disease.

Each class contains **40 images**:
- **Leaf Smut**
- **Brown Spot**
- **Bacterial Leaf Blight**

## Workflow

1. Load and preprocess images.
2. Build CNN model.
3. Train the model with and without data augmentation.
4. Evaluate performance using accuracy and loss.
5. Compare results to observe the effect of augmentation.

## Tools and Libraries

- Python
- TensorFlow / Keras
- Matplotlib
- Scikit-learn

## Results

| Model                  | Accuracy |
|-----------------------|----------|
| Without Augmentation  |  74%     |
| With Augmentation     |  87%     |

# Contact
For any inquiries, reach out via GitHub or email.

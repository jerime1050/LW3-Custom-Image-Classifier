# LW3-Custom-Image-Classifier
### (https://colab.research.google.com/drive/1mVAo4EfkorfGsv-5tQMGPbyDK-tby1wB?usp=sharing)
# Vegetable Crops Image Classification using CNN

## Student Reflection & Explanation

### 1. Dataset Preparation

**How did you organize your dataset in Google Drive?**  
I organized my dataset in Google Drive by creating a main folder for the vegetable crops dataset. Inside the folder, I created separate subfolders for each vegetable class such as tomato, cabbage, carrot, and eggplant. Each folder contains images of the specific vegetable crop. This organization helps the system easily recognize and label the images during training.

**Why is folder structure important for TensorFlow image loading?**  
Folder structure is important because TensorFlow automatically uses the folder names as labels for the images. When images are organized into folders by category, the system can easily identify which class each image belongs to during training.

---

### 2. Model Training

**What is the role of convolutional layers in image classification?**  
Convolutional layers detect important features in images such as edges, shapes, textures, and colors. These features allow the model to understand patterns in the vegetable crop images and classify them correctly.

**Why do we split data into training and validation sets?**  
The dataset is divided into training and validation sets so the model can learn from one portion of the data and be tested on another portion. This helps evaluate the model's ability to classify new images that it has not seen before.

---

### 3. Performance Analysis

**What accuracy did your model achieve?**  
Based on the training results, the model achieved approximately **81% validation accuracy**, which means the model was able to correctly classify most of the vegetable crop images.

**How did the number of images affect the model’s performance?**  
The number of images affects the model’s performance because a larger dataset provides more examples for the model to learn from. More images usually improve the accuracy and reliability of the model.

---

### 4. Critical Thinking

**What challenges did you encounter while using your own dataset?**  
One challenge was collecting enough images for each vegetable category. Some images also had different lighting conditions, backgrounds, and angles, which made classification more difficult for the model.

**How can data augmentation improve your model?**  
Data augmentation improves the model by creating modified versions of existing images, such as rotating, flipping, zooming, or adjusting brightness. This increases dataset diversity and helps the model generalize better.

---

### 5. Application

**Suggest a real-world application for your trained model.**  
A possible real-world application is an agriculture support system that can automatically identify vegetable crops from images. Farmers could use this system to recognize crops or monitor plants.

**How can this system be integrated into a mobile or web application?**  
The trained model can be integrated into a mobile or web application where users can upload or capture images of vegetable crops. The system will process the image and display the predicted classification result.

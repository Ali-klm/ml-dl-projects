# Traffic Sign and Object Detection using YOLOv8

This project focuses on detecting and classifying traffic signs and road objects using the YOLOv8 model. The workflow includes dataset preparation, training, validation, and evaluation of object detection models on custom datasets.

## 🎯 Project Goal

To detect and classify traffic signs or objects in images using YOLOv8 with PyTorch and Ultralytics framework.

---

## 📁 Project Structure

- **`project_Part_2_1.ipynb`**:  
  Trains a YOLOv8 model on a traffic sign dataset (YOLO format). Includes:
  - Dataset download from KaggleHub
  - File restructuring
  - Model training with a custom YAML config
  - Validation and prediction on the test set
  - Visualization of predictions

- **`project_Part_2_2.ipynb`**:  
  Trains another YOLOv8 model on a different dataset (object detection in cars). Includes:
  - Dataset analysis (image/label count, dimensions)
  - Custom PyTorch `Dataset` class
  - Data augmentation using torchvision
  - Model training and evaluation

---

## 🧠 Key Features

- Custom dataset formatting (train/valid/test splits)
- Training on two different datasets
- Visualization of YOLOv8 predictions
- Evaluation metrics from the Ultralytics framework
- Use of data augmentation in the second part

---

## 🗂 Dataset Sources

- [Traffic Signs YOLO Dataset](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-dataset-in-yolo-format)
- [Object Detection Car Dataset](https://www.kaggle.com/datasets/hasibullahaman/objectdetectioncar)

> Both datasets are downloaded using `kagglehub`.

---

## 🚀 Requirements

Install dependencies using:

```bash
pip install ultralytics opencv-python numpy matplotlib tqdm torch torchvision

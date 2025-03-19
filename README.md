# blood_cell_ditection
Blood Cell Detection

The project fine-tuned a RetinaNet model  for detecting three types of blood cells (Red Blood Cells (RBCs), White Blood Cells (WBCs), and Platelets) in microscopic images from the BCCD dataset.

Features:
Blood cell detection using YOLO

Image augmentation with albumentations

Model training and evaluation

Installation

Ensure you have Python installed, then install the required dependencies:
pip install -q albumentations ultralytics

Clone the dataset:
git clone https://github.com/Shenggan/BCCD_Dataset

Usage
Open the Google Colab:

Run the cells step by step to:

Load and preprocess the dataset

Train the YOLO model

Evaluate model performance:
Mean Average Precision (mAP@0.5): Measures the detection accuracy for different thresholds.

Mean Average Precision (mAP@0.5:0.95): A more comprehensive metric for model performance.

Class-specific Metrics:

RBC: Precision, Recall, AP50, AP, Accuracy

WBC: Precision, Recall, AP50, AP, Accuracy

Platelets: Precision, Recall, AP50, AP, Accuracy

Overall Accuracy: 0.87


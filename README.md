# Satellite Image Land Classification using CNN

An automated deep learning solution designed to classify diverse land types and terrains from satellite imagery. Utilizing a custom Convolutional Neural Network (CNN) architecture, this model achieves high performance and accuracy in identifying land use patterns, providing valuable insights for urban planning, environmental monitoring, and geographic studies.

---

### Application Preview
<!-- Place your system screenshots, architecture diagrams, or results charts below -->
<table>
  <tr>
    <td><strong>Dataset Samples</strong></td>
    <td><strong>Model Architecture / Results</strong></td>
  </tr>
  <tr>
    <td><img src="path/to/dataset-screenshot.png" alt="Dataset Terrain Samples" width="400"/></td>
    <td><img src="path/to/results-screenshot.png" alt="Training Accuracy Curve" width="400"/></td>
  </tr>
</table>

---

## Key Features
- High-Accuracy Classification: Implements a deep Convolutional Neural Network (CNN) optimized for remote sensing data.
- Robust Performance: Achieves 90% accuracy on automated land type classification benchmarks.
- Multi-Class Processing: Capable of segmenting and distinguishing various geographical terrains such as urban, water bodies, agricultural land, and forests.
- End-to-End Pipeline: Includes complete data preprocessing, image augmentation, feature extraction, and evaluation modules.

## Tech Stack & Libraries
- Language: Python
- Deep Learning Framework: TensorFlow / Keras
- Data & Image Processing: OpenCV, NumPy, Pandas, Pillow
- Visualization: Matplotlib, Seaborn

## Dataset Overview
The dataset contains high-resolution satellite patches categorized across distinct terrain classes. The pipeline performs structural steps including:
- Resizing and normalization of spectral bands.
- Training and Validation data splitting.
- Real-time data augmentation (rotations, flips, zoom) to prevent model overfitting.

## Model Performance
Through optimized hyperparameters and custom-layered CNN architecture, the model achieved the following metrics on evaluation datasets:
- Test Accuracy: 90%
- Loss Optimization: Evaluated using categorical cross-entropy with early stopping policies to maximize generalization.

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/topmasum/satellite-image-land-classification.git](https://github.com/topmasum/satellite-image-land-classification.git)
   cd satellite-image-land-classification

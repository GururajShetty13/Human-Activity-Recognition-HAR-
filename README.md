# Human Activity Recognition (HAR)

## Project Overview
This project addresses the challenges of Human Activity Recognition (HAR) in real-world scenarios, focusing on diverse and noisy datasets. By integrating Temporal Convolutional Networks (TCN), Dynamic Time Warping (DTW), and Dynamic Time Warping Barycenter Averaging (DBA), the project enhances HAR performance using the WEAR dataset, which comprises 18 activities from 18 subjects captured via inertial sensors.

---

## Key Features
- **Temporal Dependency Modeling:** Utilizes TCN for capturing long-range temporal dependencies.
- **Data Segmentation:** Implements DTW to align and segment time-series data.
- **Data Augmentation:** Applies DBA to create synthetic samples, improving model robustness.
- **Comprehensive Evaluation:** Analyzes precision, recall, F1-score, and accuracy metrics.

---

## Objectives
- Develop a robust HAR system for real-world conditions.
- Enhance model generalization through data augmentation.
- Evaluate and optimize the performance of TCN-based architectures.

---

## Skills Demonstrated
- **Deep Learning:** Designed and optimized TCN models for time-series data.
- **Time-Series Analysis:** Implemented DTW and DBA for segmentation and augmentation.
- **Data Preprocessing:** Normalized and segmented sensor data for model training.
- **Performance Metrics:** Evaluated model performance using cross-validation and statistical analysis.

---

## Components and Implementation
### Dataset:
- **WEAR Dataset:** 18 activities performed by 18 individuals using inertial sensors.
  - Activities include jogging, stretching, push-ups, sit-ups, and more.
  - Sensors: Accelerometers and gyroscopes.

### Methods:
1. **Dynamic Time Warping (DTW):**
   - Aligns time-series data to account for variations in activity speed and duration.
   - Segments data based on activity variations.
2. **Dynamic Time Warping Barycenter Averaging (DBA):**
   - Augments the dataset by creating synthetic samples from averaged time-series data.
   - Enhances variability and model robustness.
3. **Temporal Convolutional Networks (TCN):**
   - Captures temporal dependencies with dilated convolutions and residual connections.
   - Processes input data through temporal blocks followed by global pooling and classification.

---

## Installation and Usage
### Requirements:
- Python 3.8 or above
- Libraries: TensorFlow, NumPy, SciPy, Matplotlib

### Steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/human-activity-recognition.git

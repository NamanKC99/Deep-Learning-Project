
📖 Project Overview:

This project implements a Human Activity Recognition (HAR) system that identifies physical activities performed by users. By leveraging deep learning models, the system processes time-series data captured from smartphone sensors (Accelerometer and Gyroscope) to classify human movement into discrete categories like walking, sitting, or standing.
🚀 Key Features
 * Sensor Fusion: Combines data from 3-axial linear acceleration and 3-axial angular velocity.
 * Time-Series Classification: Uses sequential data windows to recognize patterns in movement over time.
 * Deep Learning Models: Features implementations of advanced architectures such as:
   * CNN (Convolutional Neural Networks): For spatial feature extraction from sensor signals.
   * LSTM (Long Short-Term Memory): To capture temporal dependencies in human motion.
 * Preprocessing Pipeline: Includes noise filtering, signal normalization, and sliding window segmentation (128 readings per window).
📊 Dataset Details
The project is designed to work with the UCI Human Activity Recognition Dataset, which includes recordings of 30 subjects performing six basic activities:
 * Walking
 * Walking Upstairs
 * Walking Downstairs
 * Sitting
 * Standing
 * Laying
🛠️ Tech Stack
 * Language: Python 3.x
 * Deep Learning: TensorFlow / Keras
 * Data Analysis: Pandas, NumPy
 * Visualization: Matplotlib, Seaborn
 * Environment: Jupyter Notebook / Google Colab
🧠 Model Architecture
The core model utilizes a Hybrid CNN-LSTM or Stacked LSTM approach:
 * Input Layer: Receives a 128x9 tensor (9 features: 3-axis accel, 3-axis gyro, and 3-axis total accel).
 * LSTM Layers: Learns the "rhythm" and sequence of the activity.
 * Dense Layer: Softmax activation to output the probability for each of the 6 activity classes.
📈 Results & Evaluation
The model's performance is evaluated using:
 * Accuracy: Measures overall correctness.
 * Confusion Matrix: To visualize which activities are most frequently confused (e.g., Sitting vs. Standing).
 * Loss Curves: To monitor training progress and prevent overfitting.
📥 Installation & Usage
 * Clone the Repository:
   git clone https://github.com/NamanKC99/Deep-Learning-Project.git

 * Unzip the Project:
   Locate Human_Activity_Recognization.zip and extract its contents.
 * Install Requirements:
   pip install -r requirements.txt

 * Run the Notebook:
   Open the .ipynb file in Jupyter or Colab to begin training and testing.
💡 Potential Applications
 * Healthcare: Fall detection for elderly patients.
 * Fitness: Automated workout tracking in smartwatches.
 * Smart Homes: Context-aware lighting and climate control based on user activity.

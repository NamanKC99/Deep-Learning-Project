​📋 Project Description
​Human Activity Recognition (HAR) is a key area in mobile health and context-aware computing. This project leverages Deep Learning (typically using Convolutional Neural Networks (CNNs) or Long Short-Term Memory (LSTM) networks) to identify specific human movements based on sensor data.
​The system processes data from smartphone sensors—specifically the accelerometer and gyroscope—to classify physical activities in real-time or from recorded datasets.
​🚀 Key Features
​Time-Series Analysis: Processes sequential data from 3-axial linear acceleration and 3-axial angular velocity.
​Multi-Class Classification: Successfully recognizes various activities such as:
​🚶 Walking
​🪜 Walking Upstairs / Downstairs
​🪑 Sitting
​🚶‍♂️ Standing
​🛌 Laying
​End-to-End Pipeline: Covers data preprocessing (noise filtering, sliding window splitting), feature extraction, and model evaluation using confusion matrices and accuracy scores.
​🛠️ Tech Stack
​Language: Python
​Deep Learning Frameworks: TensorFlow / Keras or PyTorch
​Data Libraries: NumPy, Pandas, Matplotlib, Scikit-learn
​Dataset: (Specify your dataset, e.g., UCI HAR Dataset or WISDM)
​🧠 Model Architecture
​The project explores advanced neural network architectures designed for spatial and temporal feature extraction:
​CNN (1D): Extracts local patterns across sensor signal windows.
​LSTM / GRU: Captures temporal dependencies and the "flow" of movement over time.
​Hybrid CNN-LSTM: Combines spatial feature extraction with temporal sequence modeling for high-precision results.

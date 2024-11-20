# Human Activity Recognition Using CNN and LSTM  

## Project Overview  
This project implements human activity recognition on videos using a combination of Convolutional Neural Networks (CNN) and Long Short-Term Memory networks (LSTM). The goal is to classify activities in video data effectively by leveraging deep learning techniques.  

## Key Features  
- **Activity Recognition**: Classifies different human activities from video footage.  
- **Dual Architecture**: Utilizes two architectures—ConvLSTM and LRCN (Long-term Recurrent Convolutional Networks) for improved performance.  
- **Data Handling**: Includes steps for downloading, visualizing, and processing the dataset.  

## Steps to Implement  

### 1. Download and Visualize Data  
- Acquire the dataset containing labeled videos.  
- Visualize the data to understand the distribution of activities.  

### 2. Process the Dataset  
- Preprocess the video data for model compatibility.  
- Extract relevant features for training.  

### 3. Split the Data  
- Divide the dataset into training and testing sets to evaluate model performance.  

### 4. Implement Models  
- **ConvLSTM Approach**:  
  Combine CNN for spatial feature extraction with LSTM for temporal sequence learning.  
- **LRCN Approach**:  
  Integrate CNN with LSTM to handle sequences of frames effectively.  

### 5. Model Testing  
- Evaluate the best-performing model using additional video samples, including YouTube videos.  

## Technologies Used  
- **Programming Language**: Python  
- **Deep Learning Frameworks**: PyTorch  
- **Libraries**: OpenCV for video processing  

## Installation  
To run this project, ensure you have the following installed:  

```bash  
pip install torch torchvision opencv-python  

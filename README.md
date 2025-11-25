# Parking Space Occupancy Classification

A machine learning and deep learning project for classifying parking spaces as occupied or vacant using Support Vector Machines (SVM) and Convolutional Neural Networks (CNN).

## Team Members
- Shatha Alshaikh (2206240)
- Manar Alharbi (22067122)
- Rasha Alsabouni (21295093)
- Gala Omar Aldossary (2210656)
- Sarah Algarni (2205539)

## Project Overview

This project implements and compares multiple approaches to parking space occupancy detection:

**Machine Learning Approach:**
- SVM with HOG (Histogram of Oriented Gradients) features
- SVM with ORB (Oriented FAST and Rotated BRIEF) features
- SVM with LBP (Local Binary Patterns) features

**Deep Learning Approach:**
- Custom CNN architecture

## Key Results

The SVM model with HOG features achieved the best performance:
- **HOG + SVM: 97.43% accuracy** ⭐
- LBP + SVM: 86.83% accuracy
- ORB + SVM: 51.71% accuracy

## Project Structure

1. **Data Loading & Preprocessing**: Image loading and train/validation split
2. **Feature Extraction**: HOG, ORB, and LBP feature extraction for SVM models
3. **SVM Training**: 3-fold cross-validation for each feature type
4. **CNN Architecture**: Deep learning model for comparison
5. **Evaluation**: Performance metrics and visualizations

## Dataset used
PKLot dataset https://www.kaggle.com/datasets/ammarnassanalhajali/pklot-dataset


## Technologies Used

- Python 3.x
- NumPy
- OpenCV
- scikit-learn
- TensorFlow/Keras
- Matplotlib


## Course Information

**Course**: CPCS433 - Artificial Intelligence Topics
**Institution**: King Abdualziz University

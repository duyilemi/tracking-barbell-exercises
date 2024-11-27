

---

# Barbell Exercise Classification and Repetition Counting

## **Project Objective**  
This project aims to develop Python scripts for processing, visualizing, and modeling accelerometer and gyroscope data collected during gym workouts.  
The end goal is to build a **machine learning model** capable of:  
1. **Classifying barbell exercises**, including:  
   - Bench Press  
   - Deadlift  
   - Overhead Press  
   - Barbell Row  
   - Squat  
2. **Counting repetitions** of these exercises accurately.

---

## **Key Features**  
### **Data Processing**  
- Efficiently handles raw sensor data using **Pandas** for cleaning, splitting, and organizing.  
- Detects and mitigates **outliers** to improve data integrity.  

### **Data Visualization**  
- Provides clear visualizations of time-series accelerometer and gyroscope data.  
- Enables insights into exercise-specific movement patterns.  

### **Feature Engineering**  
- Extracts meaningful features to enhance classification accuracy.  
- Implements **PCA** and clustering for dimensionality reduction and pattern recognition.  

### **Machine Learning Model**  
- Trains and optimizes classifiers to accurately identify exercise types.  
- Delivers high-performance predictions through tested algorithms.  

### **Repetition Counting**  
- Includes a custom algorithm to accurately detect and count exercise repetitions.  
- Ensures real-time compatibility for tracking workouts dynamically.  

---

## **Project Background**  
- **Data Source**: Meta Motion sensor by Ambient Lab, worn on the wrist during workouts.  
- **Participants**: Five individuals performing various barbell exercises.  
- **Data Characteristics**:  
  - Captures distinct movement patterns for each exercise.  
  - Provides time-series accelerometer and gyroscope readings.  

This dataset allows for precise classification and repetition counting through advanced analytics.

---

## **End Goal**  
Deliver a system capable of:  
1. Predicting exercise types based on real-time sensor data.  
2. Counting repetitions to assist with automated fitness tracking.

---

## **Project Workflow**  
1. **Data Collection**:  
   - Load accelerometer and gyroscope CSV files.  
   - Extract features such as participant ID, exercise type, and set details.  

2. **Data Preprocessing**:  
   - Handle missing values, outliers, and anomalies.  
   - Normalize and split data for training and testing.

3. **Visualization and Analysis**:  
   - Visualize sensor readings to understand patterns.  
   - Correlate sensor axes with exercise types.

4. **Feature Engineering**:  
   - Filter noise and apply PCA.  
   - Extract and cluster relevant features.

5. **Model Development**:  
   - Train classifiers (RandomForestClassifier, SVM, DecisionTreeClassifier, GaussianNB, KNeighborsClassifier e.t.c.).  
   - Evaluate and optimize model performance.

6. **Repetition Counting**:  
   - Develop a robust algorithm to detect movement cycles for repetition tracking.  


---

## **Technologies Used**  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TensorFlow/PyTorch  
- **Development Environment**: Visual Studio Code  

---

## **Future Enhancements**  
- Integrating real-time sensor data streaming.  
- Expanding to classify additional exercises.  
- Enhancing the model to adapt to individual movement styles.

---

Contributions and feedback are welcome!  
Let’s innovate in fitness tracking together. 🚀  

---



# 📊 Machine Learning Project Repository

Welcome to our **Machine Learning Project Repository**! This project was completed as part of the CS412 course under the guidance of Prof. Onur Varol. The repository includes our work on both **classification** and **regression** tasks, along with a detailed report analyzing our methods, experiments, and results. Below, you'll find a structured overview of the repository, its components, and insights into our work.

---

## 📂 Repository Structure

### **1. Notebooks**
Here are the key Jupyter Notebooks that form the backbone of our project:

1. **`classification_training_model.ipynb`**  
   - **Purpose:** Preprocesses the dataset and trains the classification models.  
   - **Key Features:**  
     - Extensive data preprocessing and feature engineering.  
     - Fine-tuning of the BERTurk model for the final classification task.  
     - Use of TF-IDF and Naive Bayes in earlier phases.  

2. **`classification_prediction_model.ipynb`**  
   - **Purpose:** Generates predictions using the trained classification models.  
   - **Key Features:**  
     - Implements fine-tuned BERTurk for final predictions.  
     - Documents results and evaluates performance on test data.

3. **`regression_model.ipynb`**  
   - **Purpose:** Handles the regression task from data preprocessing to predictions.  
   - **Key Features:**  
     - Initial neural network implementation and analysis.  
     - Incorporates advanced regression techniques (e.g., Random Forest, LightGBM).  
     - Ensemble modeling for final predictions.  
     - Outlier handling and extensive preprocessing.

4. **`requirements.txt`**
   - **Purpose:** Contains the required Python libraries for the notebooks
   - **Usage:** `pip install -r requirements.txt`

---

## 📑 Project Report
The **detailed project report** provides a comprehensive analysis of our approach and results for both classification and regression tasks. Here's what it covers:  

### **Classification Task**
- Baseline implementation using TF-IDF and Naive Bayes.
- Incorporation of custom neural networks and ensemble modeling.
- Challenges encountered in earlier phases.
- Final solution with BERTurk, demonstrating significant improvements.  

### **Regression Task**
- Exploration of custom metrics and data correlations.  
- Early attempts with neural networks and their limitations.  
- Integration of advanced regression models and ensemble learning.  
- Final results and key takeaways.

---

## 🚀 Methodology

### **General Workflow**
1. **Data Preprocessing:**  
   - Cleaned and normalized data across all tasks.  
   - Extracted emojis and engineered features for classification.  
   - Removed outliers for regression tasks.  

2. **Model Development:**  
   - Iterative approach with TF-IDF, neural networks, and ensemble methods.  
   - Fine-tuned BERTurk for classification.  
   - Leveraged tree-based models for regression.  

3. **Evaluation:**  
   - Cross-validation to ensure model robustness.  
   - Local evaluation datasets and instructor-provided test datasets.  

4. **Experimentation:**  
   - Explored techniques like SMOTE for class imbalance.  
   - Hyperparameter tuning for all major models.

---

## 💡 Key Insights

- Early-stage overconfidence in custom neural networks taught us the importance of balancing ambition with practicality.  
- Incorporating advanced models like BERTurk and ensemble methods significantly enhanced our results.  
- Comprehensive data preprocessing and feature engineering are critical for success.  

---

## 🤝 Team Contributions

- Denizhan Altan 
- Emre Çavuş   
- İlhan İskurt 
- Alp Yelekçi  
- Serhat Cemal Öztürk  



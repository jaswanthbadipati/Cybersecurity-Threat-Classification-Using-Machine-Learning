# **README: Cybersecurity Threat Classification Using Machine Learning**

## **Project Overview**
This project classifies cybersecurity threats using machine learning models. The dataset is preprocessed, and models such as Random Forest, SVM, and Neural Networks are trained and evaluated.

## **Requirements**
Ensure you have the following dependencies installed before running the code:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
```

## **How to Run the Code**

1. **Clone the Repository** (if applicable)
   ```bash
   git clone <repository_link>
   cd <repository_folder>
   ```

2. **Run the Jupyter Notebook**
   - Open Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Navigate to `Cybersecurity_Threat_Classification_Using_Machine_Learning.ipynb` and open it.
   - Run all cells in sequence to execute the preprocessing, training, and evaluation steps.

3. **Dataset Preparation**
   - Place the dataset file (`Test_data.csv`) in the same directory as the notebook.
   - Ensure the dataset is formatted correctly and contains necessary network traffic features.

4. **Understanding the Output**
   - The models will be trained and evaluated using accuracy, precision, recall, and F1-score.
   - Confusion matrices and feature importance graphs will be generated for analysis.

5. **Modifying the Code**
   - To use a different dataset, update the file path in the data loading section.
   - Hyperparameters can be adjusted in the model training sections.

## **Results**
- **Random Forest Accuracy:** 99.91%
- **SVM Accuracy:** 99.87%
- **Neural Network Accuracy:** 99.84%

## **Future Improvements**
- Experiment with more advanced models such as deep learning architectures.
- Optimize hyperparameters for better performance.
- Deploy the model for real-time threat detection.

## **Contact & Contributions**
Feel free to contribute or raise issues via GitHub. For inquiries, contact [jaswanthbadipati@gmail.com].


# Machine Learning Techniques Laboratory

A collection of **Machine Learning laboratory experiments** implemented using Python and popular Machine Learning libraries and tools.

This repository contains implementations and experiments covering fundamental concepts of **Machine Learning, Data Preprocessing, Dimensionality Reduction, Association Rule Mining, Classification, Clustering, Neural Networks, Perceptrons, and Hyperparameter Tuning**.

---

## 📚 Course Information

- **Course:** Machine Learning Techniques Laboratory
- **Course Code:** 10211AD223
- **Department:** Artificial Intelligence and Data Science
- **Academic Year:** 2025–2026
- **Semester:** Summer Semester
- **Programming Language:** Python
- **Primary Platform:** Google Colab
- **Other Tools:** Orange, RapidMiner

---

## 🧪 Experiments

### 1. Find-S and Candidate Elimination

Implementation of:

- Find-S Algorithm
- Candidate Elimination Algorithm
- Comparison of both algorithms
- Understanding hypothesis spaces and version spaces

The experiment uses weather-related training examples to determine the most specific hypothesis.

---

### 2. Data Preprocessing, Analysis and Visualization

Perform basic data analysis and preprocessing using a dataset.

Topics covered:

- Dataset loading
- Missing-value handling
- Data inspection
- Categorical variable encoding
- Data analysis
- Distribution visualization
- Scatter plots
- Exploratory Data Analysis

**Tool:** Orange  
**Language:** Python

---

### 3. PCA and LDA

Implementation and comparison of:

- Principal Component Analysis (PCA)
- Linear Discriminant Analysis (LDA)

The experiment demonstrates dimensionality reduction on a high-dimensional dataset and compares the transformed representations using visualization and classification performance.

**Libraries:**

- NumPy
- Matplotlib
- Scikit-learn

---

### 4. Apriori and FP-Growth

Association rule mining using:

- Apriori Algorithm
- FP-Growth Algorithm

The experiment identifies frequent itemsets and generates association rules from transaction data.

Important concepts include:

- Support
- Confidence
- Lift
- Frequent Itemsets
- Association Rules

**Tools:**

- RapidMiner
- Python
- Google Colab

---

### 5. Classification

Build a Machine Learning classification model capable of analyzing and classifying new samples.

The experiment includes calculation of:

- Classification Rate
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The Iris dataset and classification algorithms are used for demonstration.

**Libraries:**

- NumPy
- Scikit-learn
- Matplotlib

---

### 6. Regression

Implementation of regression techniques including:

#### Linear Regression

Evaluation using:

- R² Score
- Mean Squared Error (MSE)

#### Multiple Linear Regression

Includes:

- Exploratory Data Analysis
- Correlation analysis
- Multiple predictors
- Multicollinearity analysis

#### Logistic Regression

Includes:

- Log-odds / Logit function
- Binary classification
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

### 7. Clustering

Implementation of both:

#### Partitioning Clustering

Example:

- K-Means Clustering

#### Hierarchical Clustering

The results are compared using appropriate clustering evaluation metrics.

Topics include:

- Cluster formation
- Distance measurement
- Cluster visualization
- Evaluation of clustering quality

---

### 8. Backpropagation Neural Network

Implementation of a neural network using image data.

The experiment demonstrates how an Artificial Neural Network can learn features from image data through:

1. Forward propagation
2. Loss calculation
3. Backpropagation
4. Weight updates
5. Model evaluation

**Platform:** Google Colab  
**Language:** Python

---

### 9. Perceptron and MLP

Implementation of a Perceptron for solving linearly separable problems.

The experiment includes:

- Perceptron implementation
- Logical gate implementation
- MLP from scratch
- NumPy-based neural network
- Backpropagation
- Classification
- Model evaluation

Logical gates such as **AND** and **OR** can be demonstrated using the perceptron model.

---

### 10. Hyperparameter Tuning

Optimization of Machine Learning models using:

- Grid Search
- Random Search

The experiment compares model performance:

**Before tuning → Hyperparameter optimization → After tuning**

This demonstrates how appropriate hyperparameter selection can affect model performance.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| NumPy | Numerical computation |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| Scikit-learn | Machine Learning algorithms |
| Mlxtend | Association rule mining |
| PyFPGrowth | FP-Growth |
| Google Colab | Experiment execution |
| Orange | Data preprocessing and visualization |
| RapidMiner | Association rule mining |

---

## 📂 Repository Structure

```text
Machine-Learning-Techniques-Lab/
│
├── Experiment-01/
│   ├── find_s.py
│   ├── candidate_elimination.py
│   └── README.md
│
├── Experiment-02/
│   ├── preprocessing.py
│   ├── visualization.py
│   └── README.md
│
├── Experiment-03/
│   ├── pca.py
│   ├── lda.py
│   └── README.md
│
├── Experiment-04/
│   ├── apriori.py
│   ├── fp_growth.py
│   └── README.md
│
├── Experiment-05/
│   ├── classification.py
│   └── README.md
│
├── Experiment-06/
│   ├── regression.py
│   ├── logistic_regression.py
│   └── README.md
│
├── Experiment-07/
│   ├── kmeans.py
│   ├── hierarchical_clustering.py
│   └── README.md
│
├── Experiment-08/
│   ├── neural_network.py
│   └── README.md
│
├── Experiment-09/
│   ├── perceptron.py
│   ├── mlp_from_scratch.py
│   └── README.md
│
├── Experiment-10/
│   ├── grid_search.py
│   ├── random_search.py
│   └── README.md
│
├── datasets/
│
├── outputs/
│
├── requirements.txt
│
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/machine-learning-techniques-lab.git
```

Navigate to the project:

```bash
cd machine-learning-techniques-lab
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

---

## 📦 Requirements

Example `requirements.txt`:

```text
numpy
pandas
matplotlib
scikit-learn
mlxtend
pyfpgrowth
seaborn
```

---

## ▶️ Running the Experiments

Most experiments can be executed using **Google Colab**.

Alternatively, run Python files locally:

```bash
python experiment.py
```

For Jupyter notebooks:

```bash
jupyter notebook
```

---

## 📊 Learning Outcomes

After completing these experiments, the learner will be able to:

- Understand fundamental Machine Learning algorithms
- Implement concept-learning algorithms
- Perform data preprocessing
- Analyze and visualize datasets
- Apply dimensionality reduction
- Generate association rules
- Build classification models
- Implement regression models
- Apply clustering algorithms
- Build basic neural networks
- Implement perceptrons and MLPs
- Perform hyperparameter optimization
- Evaluate Machine Learning models using appropriate metrics

---

## 📈 Evaluation Metrics

Different experiments use different evaluation metrics, including:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC
- Mean Squared Error
- R² Score
- Support
- Confidence
- Lift
- Clustering evaluation metrics

---

## 🎯 Learning Focus

The main focus of this repository is to understand **how Machine Learning algorithms work through practical implementation**, rather than treating Machine Learning models as black boxes.

The experiments progress from basic concept learning and preprocessing to dimensionality reduction, association mining, classification, clustering, neural networks, and model optimization.

---

## 📖 Reference

This repository is based on the **Machine Learning Techniques Laboratory Manual – 10211AD223**, Department of Artificial Intelligence and Data Science.

The laboratory manual includes the experiment syllabus covering Find-S, Candidate Elimination, preprocessing, PCA/LDA, Apriori/FP-Growth, classification, clustering, neural networks, perceptron/MLP, and hyperparameter tuning.

---

## 👨‍💻 Author

**Chandu**

B.Tech – Computer Science Engineering  
Artificial Intelligence & Machine Learning

---

## ⭐ Acknowledgement

This repository was created for academic learning and practical implementation of Machine Learning concepts.

If you find this repository useful, consider giving it a ⭐ star!

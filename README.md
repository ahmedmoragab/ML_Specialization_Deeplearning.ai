# ML Specialization - Deeplearning.ai

In this repository, I showcase my solutions to the practice lab exercises from the **Machine Learning Specialization** offered by **Deeplearning.ai** and **Stanford University**, taught by Andrew Ng.

This specialization provides a broad introduction to modern machine learning, covering everything from basic algorithms to advanced AI strategies.

## Specialization Structure

The specialization consists of three comprehensive courses:

### 1. Supervised Machine Learning: Regression and Classification

This course focuses on the foundations of machine learning. It covers building machine learning models in Python to solve regression and classification problems.

* **Key Topics:** Linear Regression, Logistic Regression, Gradient Descent, Overfitting, and Regularization.

### 2. Advanced Learning Algorithms

This course explores the world of Artificial Intelligence, focusing on neural networks and decision trees.

* **Key Topics:** Neural Networks, Activation Functions, Multiclass Classification, Decision Trees, and Random Forests.

### 3. Unsupervised Learning, Recommenders, Reinforcement Learning

The final course explores non-labeled data and specialized AI systems.

* **Key Topics:** K-means Clustering, Anomaly Detection, Recommender Systems, and Reinforcement Learning.

---

## Projects & Labs Highlighted

Each directory contains a Jupyter Notebook of the same name and all necessary supporting files (like `utils.py`) to run the implementation.

### 📈 [C1_W2_Linear_Regression]

* **Problem:** Predicting profits for a restaurant franchise based on city population.
* **Implementation:**
* Developed the **Cost Function** to measure model performance.
* Implemented **Batch Gradient Descent** from scratch using vectorization.
* Visualized the relationship between population and profit to determine the line of best fit.



### 🎯 [C1_W3_Logistic_Regression]

* **Problem:** Predicting university admission and microchip quality based on test results.
* **Implementation:**
* Built a classification model using the **Sigmoid function**.
* Implemented **Regularized Logistic Regression** to handle complex, non-linear decision boundaries without overfitting.
* Used feature mapping to transform the input data into a higher-dimensional space.



---

## 🛠 Tools and Libraries

The following libraries are essential for running the notebooks in this repository:

* **NumPy:** The core library for scientific computing, used for all vectorized implementations of cost functions and gradient descent to ensure computational efficiency.
* **Matplotlib:** Used for data visualization, plotting cost history, and rendering decision boundaries.
* **Standard Python Libraries:** Includes `copy` for handling object manipulation during optimization steps.

### Installation

You can set up your environment using the following command:

```bash
pip install numpy matplotlib

```

---

## How to Use This Repository

1. Clone the repository:
```bash
git clone https://github.com/ahmedmoragab/ML_Specialization_Deeplearning.ai.git

```


2. Navigate to a specific project directory (e.g., `cd C1_W2_Linear_Regression`).
3. Ensure the local helper scripts (e.g., `utils.py`) are present in that directory.
4. Launch Jupyter Notebook or open the files in your preferred IDE.

# **Basic Neural Network and Machine Learning Algorithms**  

This repository contains simple implementations of **fundamental neural network models and machine learning algorithms**. The codes provide a beginner-friendly introduction to how these algorithms work, with basic implementations to help understand their core principles.  

---

## **Implemented Algorithms**  

### **1. Adaptive Linear Neuron (Adaline)**
- **Adaline** is an improvement over the **Perceptron**, using a **continuous activation function** instead of a step function.  
- It minimizes the **Mean Squared Error (MSE)** rather than relying on discrete thresholding.  
- Uses **gradient descent** to update weights iteratively.  
- **Key Formula:**  
  \[
  w = w + \alpha \cdot e \cdot x
  \]
  where **\(e\)** is the error between expected and actual output.  

📌 **File:** `Addaline.ipynb`  

---

### **2. Hebbian Learning Rule**
- One of the **simplest learning rules**, inspired by **biological neurons**.  
- "Neurons that fire together, wire together"—weights increase when input and output are both active.  
- **Weight Update Rule:**  
  \[
  w = w + \alpha \cdot x \cdot y
  \]
  where \( x \) is the input and \( y \) is the output.  

📌 **File:** `Hebb-Rule.ipynb`  

---

### **3. Kohonen Self-Organizing Map (K-SOFM)**
- **Unsupervised learning algorithm** used for clustering and feature mapping.  
- Learns by adjusting weights based on proximity in a **neighborhood function**.  
- Helps visualize **high-dimensional** data in **lower dimensions**.  
- **Steps:**  
  - Find the **Best Matching Unit (BMU)**.  
  - Update BMU and neighbors.  
  - Reduce learning rate over time.  

📌 **File:** `Kohonen-self-organizing-map.ipynb`  

---

### **4. Learning Vector Quantization (LVQ)**
- **Supervised learning algorithm** based on **winner-takes-all** strategy.  
- Finds the closest reference vector (prototype) and updates it based on classification correctness.  
- Used for **classification** tasks.  

📌 **File:** `Learning-Vector-Quantization.ipynb`  

---

### **5. Linear Regression**
- **Basic supervised learning algorithm** for predicting continuous values.  
- Uses the equation:  
  \[
  y = mx + c
  \]
  - \( m \) = slope  
  - \( c \) = intercept  
- Finds the best-fit line by minimizing **Mean Squared Error (MSE)** using **Gradient Descent**.  

📌 **File:** `LinearRegression.ipynb`  

---

### **6. Logistic Regression**
- A type of **classification algorithm** (not regression).  
- Used for **binary classification** problems.  
- Uses the **sigmoid function** to output probabilities:  
  \[
  \sigma(z) = \frac{1}{1 + e^{-z}}
  \]  
- Optimized using **Gradient Descent**.  

📌 **File:** `LogisticRegression.ipynb`  

---

### **7. Multilayer Adaptive Linear Neuron (Madaline)**
- **Extension of Adaline** with multiple layers.  
- Uses **multiple adaptive linear neurons** to improve performance.  
- Trains using a **minimum disturbance rule**.  
- Can solve **non-linearly separable problems**.  

📌 **File:** `Madaline.ipynb`  

---

### **8. McCulloch-Pitts Neuron**
- **One of the earliest models** of artificial neurons.  
- Works on **binary inputs and outputs** using threshold-based activation.  
- **Equation:**  
  \[
  y = 1 \quad \text{if} \quad \sum w_i x_i \geq \theta, \quad \text{else} \quad y = 0
  \]
- Can implement **basic logic gates** (AND, OR, NOT).  

📌 **Files:**  
- `McCulloch-Pitts.ipynb`  
- `McCulloch-Pitts_Weights.ipynb`  

---

### **9. Single-Layer Perceptron**
- **Simplest neural network model**, consisting of a **single layer** of neurons.  
- Used for **linearly separable** problems.  
- Uses **Step Activation Function**:  
  \[
  y = 1 \quad \text{if} \quad \sum w_i x_i + b > 0, \quad \text{else} \quad y = 0
  \]
- **Trained using Perceptron Learning Rule:**  
  \[
  w = w + \alpha (y_{true} - y_{pred}) x
  \]  

📌 **File:** `Single-Layer-Perceptron.ipynb`  

---

### **10. Feature Mapping**
- A **preprocessing technique** that helps in improving model performance.  
- Maps **low-dimensional data** into **higher dimensions** to make it linearly separable.  
- Often used with **Support Vector Machines (SVMs)**.  
- **Example Transformations:**  
  \[
  \phi(x) = (x_1^2, x_2^2, 2x_1x_2)
  \]  

📌 **File:** `Feature-Mapping.ipynb`  

---

## **How to Run the Codes**
1. **Clone the Repository:**  
   ```
   git clone https://github.com/yourusername/your-repo.git
   ```
2. **Install Dependencies:**  
   ```
   pip install numpy matplotlib
   ```
3. **Run Jupyter Notebook or Python Scripts:**  
   ```
   jupyter notebook
   ```
   OR  
   ```
   python filename.py
   ```

---

## **Conclusion**
This repository serves as a **basic introduction** to **fundamental machine learning and neural network models**. These algorithms provide the foundation for understanding more advanced concepts like **deep learning, convolutional networks, and reinforcement learning**.  

🚀 **Explore, modify, and learn from these implementations!** 🚀  

---
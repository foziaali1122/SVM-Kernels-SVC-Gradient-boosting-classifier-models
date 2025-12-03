## ***SVM Kernel Classification Project***

### Overview

This project demonstrates how Support Vector Machine (SVM) works with different Kernels to classify complex datasets.
Focus is on understanding Linear, Polynomial, and RBF Kernels with clean preprocessing & model comparison.


---

### Main Focus: SVM Kernels

### **1. Linear Kernel**

Works when data is linearly separable

- Creates a straight-line decision boundary

- Fastest & simplest kernel


---

### **2. Polynomial Kernel**

- Handles curved relationships

- Adds polynomial degree for flexibility

- Good for medium complexity patterns



---

### 3. RBF (Gaussian) Kernel — Most Powerful

- Best for non-linear & complex datasets

- Creates smooth & flexible boundaries

- Most commonly used kernel in real-world ML



---

### Workflow (Short & Clean)

- Data Loaded using pandas

- Label Encoding for categorical features

- StandardScaler applied (important for SVM)

- SMOTE used to fix target imbalance

- SVC trained with Linear, Polynomial & RBF kernels

- Model accuracy compared



---

### Results Summary

Kernel|	Performance|

Linear||	Good for simple linearly separable data|
Polynomial||	Works well on curved boundaries|
RBF||⭐ Best overall accuracy & stability|



---

### Technologies Used

- Scikit-Learn (SVC, Kernels)

- Pandas / NumPy

- SMOTE

- Matplotlib / Seaborn



---

### Conclusion

- RBF Kernel gives the highest accuracy

- Scaling + SMOTE greatly improves model performance

- SVM is a powerful method for binary classification in any domain



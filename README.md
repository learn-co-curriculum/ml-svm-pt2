# ml-svm-pt2

Implement non-linear classifier with a support vector machine (part II)
- Kernel method/trick: explain mathematically 
- Examples of commonly used Kernels:
    - Polynomial Kernel SVM
    - Radial Kernel SVM / Radial basis function (RBF)
    - Sigmoid Kernel
- In Python: scikit-learn:
    - SVC, NuSVC (= similar to SVC, but uses a parameter to control the number of support vectors)
    - LinearSVC (Similar to SVC with parameter kernel=’linear’ but scales better)

SVM with more than 2 cases 
- Maths: how generalize what has been covered to N cases
- In Python: 
      - One-against-one approach using SVM/NuSVM
      - "One-versus-the-rest" multi-class strategy using LinearSVC

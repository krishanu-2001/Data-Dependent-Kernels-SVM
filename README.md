# Data-Dependent-Kernels-SVM
Experiments with data dependent kernels in support vector machines


# Comparison of kernels
### laplacian kernel  
Note. Laplacian kernel is different from laplacian svm (unsupervised)  
<img width="230" alt="image" src="https://user-images.githubusercontent.com/56930593/233768075-13510cd4-9b70-43a7-9fc2-05a7a30eaafb.png">

### isolation kernel  
      1. Data dependent kernel  
      2. Significantly higher number of support vectors
      3. Similar accuracy as laplacian kernel for uniform data  
<img width="230" alt="image" src="https://user-images.githubusercontent.com/56930593/233768163-766e79d8-bac5-4344-88f9-575d68894696.png">

### linear kernel  
<img width="230" alt="image" src="https://user-images.githubusercontent.com/56930593/233768183-7f2909af-1bfd-47f0-92a7-35660f27fa9d.png">



# References
* Ting, Kai Ming, Yue Zhu, and Zhi-Hua Zhou. "Isolation kernel and its effect on SVM." Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining. 2018.
* Liu, Fei Tony, Kai Ming Ting, and Zhi-Hua Zhou. "Isolation forest." 2008 Eighth IEEE International Conference on Data Mining. IEEE, 2008.
* Liu, Fei Tony, Kai Ming Ting, and Zhi-Hua Zhou. "Isolation-based anomaly detection." ACM Transactions on Knowledge Discovery from Data (TKDD) 6.1 (2012): 3.
* https://math.stackexchange.com/questions/3388518/expected-number-of-paths-required-to-separate-elements-in-a-binary-tree
* Cortes, David. "Distance approximation using Isolation Forests." arXiv preprint arXiv:1910.12362 (2019).
* Cortes, David. "Revisiting randomized choices in isolation forests." arXiv preprint arXiv:2110.13402 (2021).
* Cortes, David. "Isolation forests: looking beyond tree depth." arXiv preprint arXiv:2111.11639 (2021).
* https://jakevdp.github.io/PythonDataScienceHandbook/05.07-support-vector-machines.html

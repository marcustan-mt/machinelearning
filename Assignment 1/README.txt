
*********************
Creator: Marcus Tan (mtan75; 903757907)
Created on: 11 Feb 2024
Purpose: Assignment 1; CS7641 Machine Learning; Georgia Institute of Technology
*********************

Purpose: This file contains documents required for CS7641 Assignment 1 (Supervised Learning) for Georgia Institute of Technology.

Box Link (where all documents are kept): https://gatech.box.com/s/km9xx0bxd6wfyqpde1jhsaj3vgvnqhtm

Documents available:
- "mtan75-analysis.pdf" - This contains the PDF report that summarizes the learnings and analysis of the 5 algorithm on the 2 dataset used.
- "assignment_1.ipynb" - This contains the code that have been used to create the charts in the report.
- "winequality-white.csv" - This is the first dataset used for this assignment. This dataset can also be sourced from https://archive.ics.uci.edu/dataset/186/wine+quality
- "apple_quality.csv" - This is the second dataset used for this assignment. This dataset can also be sourced from https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality
- "images" folder - Contains EDA on the dataset. Instructors are free to ignore this folder as it contains exploratory analysis conducted on the dataset.

Libraries used:
- warnings
- matplotlib
- numpy
- datetime
- random
- pandas
- sys
- tensorflow
- tensorflow.keras
- sklearn.preprocessing
- sklearn.model_selection
- sklearn.metrics
- sklearn.tree
- time
- sklearn.ensemble
- kera.models
- keras.layers
- sklearn.neighbors
- sklearn.svm
- keras.optimizer

How do I run "assignment_1.ipynb"?
- Step 1: Download Anaconda from https://www.anaconda.com/
- Step 2: Follow the steps in Anaconda to install jupyter notebook
- Step 3: After installing, navigate to the folder where "assignment_1.ipynb" is located.
- Step 4: Open the file and run individual cells to recreate the charts (wherever needed). Charts (as well as results) have also been saved in the python notebook for easy reference.

How is the notebook structured?
- The notebook is structured into 6 components: 
	(1) Defining functions for preprocessing, 
	(2) Decision Trees, 
	(3) Ensemble learning, 
	(4) Neural Network, 
	(5) K Nearest Neighbor, 
	(6) SVM. 
Each of these components have headers which has been labelled for easy replication.
- For component 2 - 6, each of these have 5 sections where we explored:
	(a.) varying 2 or more hyperparameters for the specific algorithms, 
	(b.) Using Gridsearch to identify the optimal hyperparameters
	(c.) Deeper analysis: Converting multi-class into imbalanced binary class problem
	(d.) Deeper analysis: Converting imbalanced binary class problem into evenly distributed binary class problems
	(e.) Conducting final runs on each of the algorithm for final run time, optimal results and learning curves.


Bibliography for mtan75-analysis.pdf report:
1) Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). UC Irvine Machine Learning Repository. Retrieved from Wine Quality: https://archive.ics.uci.edu/dataset/186/wine+quality
2) Del Moral, P., Nowaczyk, S., & Pashami, S. (2023). Why Is Multiclass Classification Hard? IEEE Access, 80448-80462.
3) Elgiriyewithana, N. (2023). Kaggle. Retrieved from Apple Quality: https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality
4) Huang, Z., Sang, Y., Sun, Y., & Lv, J. (2022). A neural network learning algorithm for highly imbalanced data classification. Information Sciences, 496-513.
5) Khamis, A., Ismail, Z., Haron, K., & Mohammed, A. (2005). The Effects of Outliers Data on Neural Network Performance. Journal of Applied Sciences, 1394-1398.
6) Muhr, D., Affenzeller, M., & Kung, J. (2023). A Probabilistic Transformation of Distance-Based Outliers. arXiv.
7) Smith, A., Johnson, B., & Williams, C. (2020). The Impact of Computational Power on Modern Machine Learning. Journal of Advanced Computing, 45-57.
8 ) Tanha, J., Abdi, Y., Samadi, N., Razzaghi, N., & Mohammad, A. (2020). Boosting methods for multi-class imbalanced data classification: an experimental review. Journal of Big Data. Retrieved from https://journalofbigdata.springeropen.com/articles/10.1186/s40537-020-00349-y



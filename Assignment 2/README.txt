
*********************
Creator: Marcus Tan (mtan75; 903757907)
Created on: 3 March 2024
Purpose: Assignment 2; CS7641 Machine Learning; Georgia Institute of Technology
*********************

Purpose: This file contains documents required for CS7641 Assignment 2 (Random Optimization) for Georgia Institute of Technology.

Box Link (where all documents are kept): https://gatech.box.com/s/z93hbiprs0fmzcrfc5ei61v5gjx1ue9n

Documents available:
- "mtan75-analysis.pdf" - This contains the PDF report that summarizes the learnings and analysis of the 5 algorithm on the 2 dataset used.
- "assignment_2.ipynb" - This contains the code that have been used to create the charts in the report. Use this to replicate the charts in the report. 
- "Assignment 2 Base_RHC_Hyperparameter Tuning.ipynb" - Contains the experiments used to identify the optimal Neural Network architecture and RHC restart parameter. Instructors are free to ignore this as it contains experimentation results.
 - "Assignment 2 GA_NN_Hyperparameter Tuning.ipynb" - Contains the experiments used to identify the optimal GA NN hyperparameters. Instructors are free to ignore this as it contains experimentation results.
- "Assignment 2 SA_NN Experiment Tuning" - Contains the experiments used to identify the optimal SA NN hyperparameters. Instructors are free to ignore this as it contains experimentation results.
- "apple_quality.csv" - This is the second dataset used for this assignment. This dataset can also be sourced from https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality
- "images" folder - Contains EDA on the dataset. Instructors are free to ignore this folder as it contains exploratory analysis conducted on the dataset.
- "neural network charts.xlsx" - Contains neural network diagrams for report.

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
- mlrose_hiive (pip installed from a git clone of the folder: https://github.com/hiive/mlrose/tree/master/mlrose_hiive)

How do I run "assignment_2.ipynb"?
- Step 1: Download Anaconda from https://www.anaconda.com/
- Step 2: Follow the steps in Anaconda to install jupyter notebook
- Step 3: After installing, navigate to the folder where "assignment_1.ipynb" is located.
- Step 4: Open the file and run individual cells to recreate the charts (wherever needed). Charts (as well as results) have also been saved in the python notebook for easy reference.
Note: In situations where you are pulling in mlrose_hiive, do remember to clone from git and do an import from there. Similarly for ingesting the apple quality dataset, do remember to redirect the directory to the appropriate dataset.

How is the notebook ("assignment_2.ipynb") structured?
- The notebook is structured into 6 components: 
	(1) Defining functions for optimization problems, 
	(2) N Queens, 
	(3) TSP, 
	(4) Continuous Peak Problem, 
	(5) Neural Network
Each of these section have headers which has been labelled for easy replication.
- For section 2 - 4, each of these have 4 sections where we explored:
	(a.) Optimized hyperparameters per algorithm
	(b.) Fitness per iteration curves
	(c.) Fitness for each size
	(d.) FEval/Iteration
- For section 5, the experimentations for neural networks are conducted in each of the python notebooks: (1) Assignment 2 Base_RHC_Hyperparameter Tuning.ipynb, (2) Assignment 2 GA_NN_Hyperparameter Tuning.ipynb, (3) Assignment 2 SA_NN Experiment Tuning.ipynb. For easier plotting process, the final fitness scores/recall scores from the main python notebook (assignment_2.ipynb) is transferred over to excel (titled: neural network charts.xlsx).

Bibliography:
Elgiriyewithana, N. (2023). Kaggle. Retrieved from Apple Quality: https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality
Freedman, R. S. (2019, June 5). ArXiv. Retrieved from ArXiv: https://arxiv.org/ftp/arxiv/papers/1906/1906.04011.pdf
Smith, A., Johnson, B., & Williams, C. (2020). The Impact of Computational Power on Modern Machine Learning. Journal of Advanced Computing, 45-57.


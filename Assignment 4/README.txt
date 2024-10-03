
*********************
Creator: Marcus Tan (mtan75; 903757907)
Created on: 13 April 2024
Purpose: Assignment 4; CS7641 Machine Learning; Georgia Institute of Technology
*********************

Purpose: This file contains documents required for CS7641 Assignment 4 (Reinforcement Learning) for Georgia Institute of Technology.

Box Link (where all documents are kept): https://gatech.box.com/s/w4pbpl812wbjjpjsvq5zb8hz02ehem7m

Documents available:
- "mtan75-analysis.pdf" - This contains the PDF report that summarizes the learnings and analysis for this assignment.
- "Assignment 4 - Q Learning.ipynb" - Contains the Q Learning results received for both Blackjack and Frozen Lake
- "Assignment 4 Value Iteration and Policy Iteration.ipynb" - Contains Value Iteration and Policy Iteration results.
- "vi_pi_qLearning_differences.csv" - Contains the comparison of VI/PI/Q Learning Policies in Blackjack
- "blackjack-envP.pickle" - Pickle file that contains all the Blackjack environment information required to change the state space in Blackjack

Libraries used:
- bettermdptools
- gymnasium
- numpy
- itertools
- matplotlib
- time
- pandas

How do I run any of the ".ipynb" files?
- Step 1: Download Anaconda from https://www.anaconda.com/
- Step 2: Follow the steps in Anaconda to install jupyter notebook
- Step 3: After installing, navigate to the folder where ".ipynb" file is located.
- Step 4: Open the file and run individual cells to recreate the charts (wherever needed). Charts (as well as results) have also been saved in the python notebook for easy reference.

How are the notebooks structured?
- The 2 notebooks are intended to keep results for 2 types of RL algorithms: 
(1) "Assignment 4 Value Iteration and Policy Iteration.ipynb" - This notebook keeps the results for Value Iteration and Policy Iteration for both environments (Blackjack/Frozen Lake). It contains results specifically in 3 areas: (1) Convergence, (2) State space, (3) Printing the final policy
(2) "Assignment 4 - Q Learning.ipynb" - Similar to the earlier notebook, this python notebook also contains results specifically in 3 areas: (1) Convergence, (2) State space, (3) Printing the final policy. However, this notebook focuses more on applying Q Learning to the 2 chosen environments (Blackjack/Frozen Lake)

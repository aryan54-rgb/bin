# practice - 33 standalone AIML notebooks

Open Jupyter in this folder. Keep the data/ folder next to the notebooks.
Each numbered notebook contains its original Classroom question, simple direct
code, informative output and a final problem-specific viva guide.

Run one notebook at a time, from top to bottom with Shift+Enter.
Some cells ask for input; press Enter to use a shown default. Q7 is an interactive game.
Do not start with Run All on all 33 notebooks together.

One-time installation in your Jupyter kernel:

    %pip install pandas numpy matplotlib scikit-learn openpyxl mlxtend tensorflow

Restart the kernel if required. Install only missing packages; TensorFlow is used
only in Q30/Q31 and mlxtend only in Q29. The notebooks have commented install hints.

All 11 original Classroom datasets are included. Iris is built into scikit-learn.
Q21 additionally includes a clearly labeled synthetic spam_practice.csv because
the Classroom post had no spam file. It is for practicing code, not benchmarking.
Q19 and Q31 derive clearly labeled practice student categories/pass labels because
Student_Performance.csv contains a numeric Performance Index, not those labels.
Use the examiner's official labels/thresholds if supplied. Q24 excludes the second
Survived column in the provided Titanic file to avoid target leakage.

Suggested first notebook: 12_Salary_Linear_Regression.ipynb.

The source post says tentative / For reference only. Final exam questions may vary.
Source: https://classroom.google.com/u/0/c/ODcwNzUyMjE0NDY5/m/ODkyNjEwODMyNjQ5/details
Read VALIDATION.txt for execution results and practical limits.

## Notebook index

01. 01_A_Star_Route_Finding.ipynb
02. 02_Greedy_Best_First_Search.ipynb
03. 03_Robot_Navigation_A_Star.ipynb
04. 04_N_Queens_CSP.ipynb
05. 05_Sudoku_CSP.ipynb
06. 06_Exam_Timetable_CSP.ipynb
07. 07_Tic_Tac_Toe_Minimax.ipynb
08. 08_Eight_Puzzle_A_Star.ipynb
09. 09_Uber_EDA_PCA_Regression.ipynb
10. 10_House_Price_Linear_Regression.ipynb
11. 11_Student_Performance_Regression.ipynb
12. 12_Salary_Linear_Regression.ipynb
13. 13_Regression_With_and_Without_PCA.ipynb
14. 14_Loan_Approval_Decision_Tree.ipynb
15. 15_Customer_Churn_Decision_Tree.ipynb
16. 16_Disease_Decision_Tree.ipynb
17. 17_Decision_Tree_Gini_Entropy_Optimization.ipynb
18. 18_Iris_KNN.ipynb
19. 19_Student_Performance_KNN.ipynb
20. 20_Diabetes_KNN.ipynb
21. 21_Spam_Naive_Bayes.ipynb
22. 22_Iris_Gaussian_Naive_Bayes_vs_Tree.ipynb
23. 23_Random_Forest_vs_Decision_Tree.ipynb
24. 24_Titanic_Random_Forest.ipynb
25. 25_Customer_K_Means.ipynb
26. 26_Student_K_Means.ipynb
27. 27_Mall_Customers_K_Means.ipynb
28. 28_K_Means_Evaluation.ipynb
29. 29_Market_Basket_Apriori.ipynb
30. 30_Bank_Churn_ANN.ipynb
31. 31_Student_Pass_Fail_ANN.ipynb
32. 32_Decision_Tree_KNN_Naive_Bayes_Comparison.ipynb
33. 33_End_to_End_ML_Pipeline.ipynb

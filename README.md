# quora_dup_question_detector

Credits: Kaggle
<h3>Problem Statement</h3>

Identify which questions asked on Quora are duplicates of questions that have already been asked.
This could be useful to instantly provide answers to questions that have already been answered.
We are tasked with predicting whether a pair of questions are duplicates or not.

Source : https://www.kaggle.com/c/quora-question-pairs

<h3>Real world/Business Objectives and Constraints</h3>
1. The cost of a mis-classification can be very high.
2. You would want a probability of a pair of questions to be duplicates so that you can choose any threshold of choice.
3. No strict latency concerns.
4. Interpretability is partially important.


<h3>Data Overview</h3>
- Data will be in a file Train.csv
- Train.csv contains 5 columns : qid1, qid2, question1, question2, is_duplicate
- Size of Train.csv - 60MB
- Number of rows in Train.csv = 404,290

<h3>It is a binary classification problem, for a given pair of questions we need to predict if they are duplicate or not</h3>

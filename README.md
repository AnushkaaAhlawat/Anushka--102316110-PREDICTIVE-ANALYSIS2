# Anushka--102316110-PREDICTIVE-ANALYSIS2




The dataset used is the India Air Quality Dataset from Kaggle.  
From the dataset, the NO2 column is selected as the input variable x.

Steps followed:

1. Load the dataset using pandas.
2. Find the NO2 column and remove missing values.
3. Apply the roll number based transformation:
   z = x + a_r * sin(b_r * x)
4. Compute mean (mu) of z.
5. Compute variance and use it to calculate lambda.
6. Compute constant c.
7. Print the values of mu, lambda and c.

How to Run:

1. Keep main.py and the CSV file in the same folder.
2. Install required libraries:
   pip install numpy pandas
3. Run:
   python main.py

Output:

The program prints three values:
mu, lambda and c

These values are submitted for the assignment.

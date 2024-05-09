# Topsis-Harsh-102167002

#Description
The Topsis Python Package is a Python library that provides an implementation of the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) method. TOPSIS is a multi-criteria decision-making method used to determine the best alternative among a set of alternatives based on their performance on multiple criteria.

#Usage
Use the following command to perform TOPSIS analysis on a dataset:

topsis data.csv "1,0,1,0,1" "+,-,+,-,+"

- data.csv: Path to the input CSV file containing the dataset.
- "1,0,1,0,1": Weights for each criterion separated by commas.
- "+,-,+,-,+": Impacts for each criterion (either + for maximizing or - for minimizing).

The output will be saved in a file named output.csv.

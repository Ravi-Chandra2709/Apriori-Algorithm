# Apriori-Algorithm
This is an implementation of the Apriori Algorithm

# Apriori Algorithm Implementation

This repo is implementation of the Apriori algorithm to generate association rules based on user-supplied minimum support and minimum confidence values. The program processes input data from a file (`small.txt`) and produces various output files containing frequent itemsets, association rules, information summary, and visualizations as specified in the project description.

## Objective

The main goal of this is to develop a Python program (`association_rules_.ipynb`) that takes these arguments or parameters the minimum support, minimum confidence, input file name, and output file name. The program follows the Apriori algorithm steps to generate frequent itemsets and association rules.

## Structure

###  1:
- Reading input data
- Generating F1 (frequent 1-itemsets)
- Writing functions for output file generation and creating examples of the generated files
- Implementing code for the required plots

### 2:
- Candidate itemset generation
- Candidate pruning
- Support counting and infrequent itemset elimination

### 3:
- Candidate rule generation and elimination

## File Descriptions

- `associatioin_rules_.ipynb`: Python code implementing the Apriori algorithm.
- `small.txt`: Input file containing transaction and item IDs.
- Output files for frequent itemsets, high confidene rules, information wrt the flow.

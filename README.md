# Graphing Sorting Allogrthims By Number of Comparisons
[![My Skills](https://skillicons.dev/icons?i=python,excel,matplotlib)](https://skillicons.dev)

## Introduction

This repository is dedicated to examining the efficiency of classic sorting algorithms across different dataset orderings. It extends our analysis to include nearly sorted, random, and sorted datasets and those sorted in reverse. By systematically comparing algorithm performance on these datasets, we aim to deepen the understanding of the computational complexity involved in sorting tasks.

## Project Files
- make_sort_data.py: Generates datasets with different orderings (nearly sorted, random, sorted, and backward sorted) for algorithm testing.
- sorts.py: Implements selection, insertion, and merge sort algorithms.
- timing_util.py: Provides timing functions to measure the performance of the sorting algorithms.
- near_sorted.csv, random.csv, sorted_list.csv, backwards.csv: CSV datasets representing nearly sorted, random, sorted, and backward sorted lists, respectively.
- Nearly Sorted Sort.png, Random Sort.png, Sorted List.png, Backwards sort.png: Graphical analysis of the sorting algorithms' performance on each dataset type.

## Data Description
The datasets span various lengths and are designed to test the sorting algorithms under different conditions: nearly sorted, randomly ordered, sorted, and reverse sorted. This allows for a comprehensive assessment of each algorithm's behavior under varying initial conditions.

## Hypothesis
We anticipate that reverse-sorted datasets will be particularly challenging for certain algorithms like insertion sort, which typically excels with nearly sorted data. Conversely, due to its divide-and-conquer approach, we expect that merge sort will demonstrate robust performance across all dataset orderings.

## Requirements
Python 3.x and its libraries: matplotlib (for plotting), pandas (for data handling)

## Setup and Execution
1. Ensure you have Python 3.x installed, along with the matplotlib and pandas libraries.
2. Run make_sort_data.py to generate the dataset files if they don't already exist.
3. Use sorts.py to sort the datasets with the implemented algorithms.
4. Utilize timing_util.py to time the sorting process and output performance graphs.

##Conclusion
By incorporating reverse-sorted data, this project presents a thorough investigation into the performance of sorting algorithms. The results offer crucial insights for algorithm selection in varying scenarios, potentially guiding more efficient data processing strategies in real-world applications.

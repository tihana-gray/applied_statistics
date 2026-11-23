# Applied Statistics Assessment

This repository contains my assessment work for the Applied Statistics module.

The assessment is completed in a Jupyter Notebook and uses the Iris dataset to explore statistical concepts including distributions, correlation, hypothesis testing and analysis.

Everything needed to run the notebook is included in this repository.

## Assessment Overview

The assessment consists of four problems:
1. Problem 1: Exploring Petal Length
2. Problem 2: Correlation Between Petal Length and Petal Width
3. Problem 3: Comparing Species Using t-Tests
4. Problem 4: Comparing the Species Using ANOVA

Each problem is completed in `problems.ipynb` and includes Python code, statistical analysis, visualisations, explanations and references.

## Dataset

The assessment uses the Iris dataset, first published by Ronald Fisher in 1936. It contains 150 flowers from three species (Setosa, Versicolor and Virginica), with 50 flowers per species. Each flower has four measurements in centimetres: sepal length, sepal width, petal length and petal width.

The notebook loads the data from the [seaborn-data repository](https://github.com/mwaskom/seaborn-data/blob/master/iris.csv) on GitHub.

- Fisher, R. A. (1936). The use of multiple measurements in taxonomic problems. *Annals of Eugenics*, 7(2), 179–188.
- [UCI Machine Learning Repository: Iris](https://archive.ics.uci.edu/dataset/53/iris)


## Technologies and Libraries

The assessment uses:
- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [pandas](https://pandas.pydata.org/docs/index.html)
- [NumPy](https://numpy.org/)
- [SciPy](https://scipy.org/)
- [Matplotlib](https://matplotlib.org/)

References to documentation and examples used during the assessment are included throughout the notebook.

## Repository Structure

- `problems.ipynb` - Main Jupyter Notebook containing the assessment problems, explanations, analysis and results.
- `AGENTS.md` - AI usage guidance provided as part of the assessment requirements.
- `requirements.txt` - Python packages required to run the notebook.
- `.gitignore` - Specifies files and folders that should not be tracked by Git.

## Running the Notebook

1. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```
2. Open `problems.ipynb` in Jupyter Lab (`jupyter lab`) or VS Code.
3. Run all cells from top to bottom.

---

## Problem 1: Exploring Petal Length

Problem 1 explores the distribution of petal length for all 150 flowers in the Iris dataset and then looks at each of the three species separately: Setosa, Versicolor and Virginica.

The work includes:
- examining the number of observations for each Iris species
- calculating the mean and standard deviation of petal length
- creating histograms to examine the distribution of petal lengths
- calculating and plotting normal distribution curves using the mean and standard deviation of the data
- creating separate histograms and normal distribution curves for Setosa, Versicolor and Virginica
- calculating and comparing the mean and standard deviation for each species
- comparing the distributions and discussing how well the normal distribution fits the complete dataset and the individual species

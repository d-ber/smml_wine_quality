# Support Vector Machine & Logistic Regression for Wine Quality Prediction

This project investigates binary wine quality prediction using two classification algorithms:

- Support Vector Machine (SVM)
- Logistic Regression (LR)

Both the linear and kernel versions of SVM and LR have been implemented from scratch and evaluated on the wine physicochemical dataset from [https://archive.ics.uci.edu/dataset/186/wine+quality](https://archive.ics.uci.edu/dataset/186/wine+quality).

Three kernels have been implemented and tested for both SVM and LR: the gaussian, the polynomial and the sigmoid kernels.

## Files

- `wine.ipynb`: main notebook (includes optional kernel tuning), provided with output
- `wine_no_kernel_tuning.ipynb`: reference notebook with kernel tuning disabled,  provided with output
- `wine.pdf`: report

## How to run

1. Create and activate a Python environment (tested on Python 3.13.7).
2. Install dependencies with pip: `pip install -r requirements.txt`
3. Open `wine.ipynb` (or `wine_no_kernel_tuning.ipynb`) in Jupyter and run all cells.

<br><br>

Kernel hyperparameter tuning can be computationally expensive and may take a long time to run. 
The notebook includes a flag in the first cell to enable/disable kernel tuning.
Even with kernel tuning disabled, kernel SVM and LR are tested with arbitrary parameters, to check they work.

The accompanying report refers to the full run (including tuning). 
For a faster but limited test of the code, use `wine_no_kernel_tuning.ipynb`.

<br><br>

Note the use of the first person plural is simply a stylistic choice, I am the sole author.
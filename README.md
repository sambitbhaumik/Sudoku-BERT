# BERT Masked Language Model for Sudoku
A simple prototype to demonstrate the potential of BERT-masked language to solve non-trivial logical and combinatorial reasoning problems. In this case, we have chosen to solve sudoku puzzles by using BERT.

# Prerequisites
To run this implementation, the following packages are required:
* [Hugging Face Transformers](https://huggingface.co/docs/transformers/en/installation) with PyTorch
* [Optuna](https://pypi.org/project/optuna/) for hyperparameter optimization
* [pandas](https://pandas.pydata.org/docs/getting_started/install.html)

Download this dataset from Kaggle
    [9 Million Sudoku Puzzles](https://www.kaggle.com/datasets/rohanrao/sudoku)

# Experiments

* Training on 240000 puzzles and solutions for 5 epochs, we observed an average of over 90% correctness for every puzzle 
* Training on 240000 puzzles and solutions for 2 epochs, we observed an average of around 60% correctness for every puzzle 

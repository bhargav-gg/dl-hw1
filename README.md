# Explanation

All of my code, comments, explanations, and documentation can be found in the `main.ipynb` Jupyter Notebook.

1-1: Completed (BONUS completed for function simulation, 3 models, 2 functions | BONUS incomplete for actual task)
1-2: Incomplete
1-3: Incomplete

I make use of the following non-standard libraries in my Jupyter Notebook:
- scikitlearn (sklearn) - test_train_split function
- PyTorch, TorchVision - model creation, training, testing
- matplotlib - graphing/charting
- numpy - Array buffer between library transfers (scikitlearn -> PyTorch in test_train_split)
- tqdm - Progress meter by the epoch (disabled in Notebook, but enabled when I needed to debug)

The code can be ran in the same way any Jupyter Notebook can. Ensure you have the libraries above and a Jupyter Notebook kernel/Python installation and it should run.

Some data is taken from PyTorch's datasets library, but as you can see from the Notebook, these are downloaded to the executing user's file system. With that and the sheer quantity of the data (Git does not like large files), I have explicitly left those out. I leave that to the reader to download after running the Notebook for themselves.
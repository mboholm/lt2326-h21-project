# lt2326-h21-project
Repository for project assignment of LT2326, autumn 2021. The repository contains:

*    `baseline.ipynb`: this file contains code for counting the frequencies of labels in test and training data.
*    `data_builder.ipynb`: this file contains code for data preparation; from an xml file not in the repositort to train and test sets.
*    `lt2326-h21-project.ipynb`: this is the file containing the code for the model.
*    `simple_lt2326-h21-project.ipynb`: this file contain code for a simpler forerunner model to the propsed model; **this can be ignored**.
*    `gusbohom_lt2326_project_report.pdf`: the report for the project.
*    `data`: folder containing train and test data (`train.csv` and `test.csv`), including reduced versions (`mini_train.csv` and `mini_test.csv`) which can be used for development purposes.


The model is run through the jupyter notebook file `lt2326-h21-project.ipynb`. Overall variables, such as, directories for input and output, training files, and device (CUDA or CPU) are defined under *Meta-variables*. Batch size is defined prior defintion of dataloader. Other hyperparameters are defined after definitions of model and training function: and before actually calling the training function. Note that models must be instantiated *before* being passed to the training function. 

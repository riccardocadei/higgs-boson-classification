# ML2020 Project 1

## General Information

The repository contains the code for Machine Learning course 2020 (CS-433) project 1 (higgs boson challenge) at EPFL. More information about this challenge can be found in the folder `documents`.

### Team
The project is accomplished by team `INteam` with members:
- Riccardo Cadei: [@RiccardoCadei](https://github.com/RiccardoCadei)
- Raphael Attias: [@raphaelattias](https://github.com/raphaelattias)
- Shasha Jiang: [@dust629](https://github.com/dust629)
### Data
The data `train.csv` and `test.csv` should be found in https://github.com/epfml/ML_course/tree/master/projects/project1/data, to run the code please download and place them in the `data` folder

### Environment
The project has been developed and test with `python3.6`.
The required library for running the models and training is `numpy`.
The library for visualization is `matplotlib`.

### Results

Results to predict the test datasets are generated by running:
`python3 run.py`.
And the final results are saved in: `/data/finalsubmission.csv`.
* * *
## Project structure

### Training data
`implementations.py`: the implementation of 6 methods to train the model.

`run.py`: the results after using the selected model to predict test data.

### Processing data 
`exploration.py`: understanding the features of data with visualization.

`process_data.py`: preprocessing data for model training and prediction.

### Selecting Model

`crossvalidalidation.py`: using cross-validation to test the accuracy of different models.

`select_parameter.py`: searching for the appropriate parameters(lambda, degree etc.) for models.

### Notebook

`main.ipynb`: demonstrating the accuracy of different methods with data analysis.
 
`plots.ipynb`: visualizing the accuracy and error with different parameters.

### Report

`documents/report.pdf`: a 2-pages report about how we finished the project in detail.


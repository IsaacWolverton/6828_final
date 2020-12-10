# 6828_final
Final project for MIT grad 6.828. Predicting request service times.

### Setup and Install
Note that this repository was created using python 3.8.5 and cuda 11.1. When installing the requirements it may be neccesary to change some of the package versions if you do not have the same setup. You may also have to manually insert the virutalenv as a jupyter notebook kernel.
```
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

You will also have to install `imageflow_tool`, the instructions are [here](https://github.com/imazen/imageflow)

### Reproducing Report Results
The data that I generated is all in the `data/` directory and the code exists to load it and train a model. You can simply open `model_training.ipynb` and run all of the cells. This will replicate the results from the report (except for the random initialization of network weights).

### Questions?
Don't hesitate to reach out with questions!

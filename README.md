# Generate-TV-Scripts
TV Script Generation using Pytorch

## Datasets:
This model was trained using the Seinfeld dataset of scripts from 9 seasons. 

## Data Processing:
Exploratory analysis, cleaning, and train/test set splitting were done in the dlnd_tv_script_generation.ipynb notebook. Preprocessing steps were included in the preprocess_and_save_data in the helpers.py file.

## Model Training:
The training loop is implemented in the train_decoder function. This function will train the network over all the batches for the number of epochs given. The model progress will be shown every number of batches.

## Model Evaluation:
Test accuracy using model from scratch turned out to be 11% while the test accuracy using transfer learning was 70%. 

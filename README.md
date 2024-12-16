# ECE5831 Project Failed Approach:
## Using Kaggle Dataset:
In this approach, I tried to use the kaggle dataset here: 
I was not satisfied with the results, so I used another approach, which has the code in another repository:
Below I will explain the files in this repository:
1. __.gitignore:__ This is to ignore videos, images, and numpy arrays, and other files in the dataset I downloaded. This makes my version control in vscode easier to use.
2. __parsing_processing_training.ipynb:__ In this notebook, I did all the work for parsing the JSON file and pre-processing the data up to saving the numpy arrays.
3. __Training_asl.ipynb:__ In this notebook, I show the work I did to train the model on the data I had so far. This file also includes the method I made to load all the data saved in the pre-processing step.
4. __asl_model_0.2955.keras:__ Complex model trained that only reached 29.55% accuracy on testing data (Over-fitting).
5. __asl_model_51.keras:__ Simple model that reached 51% accuracy on testing data (no over-fitting.)
6. __train_frames_crop.txt:__ Text files with the frames range to crop for each video used in the training split, since some videos were longer than others. More details in the report.
7. __val_frames_crop.txt:__ Text files with the frames range to crop for each video used in the validation split, since some videos were longer than others. More details in the report.
8. __test_frames_crop.txt:__ Text files with the frames range to crop for each video used in the test split, since some videos were longer than others. More details in the report.

## External Links:
1. __Link to Original Dataset:__
2. __Link to pre-processed Data in Google Drive:__
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-5qSmszH)
# Project 2

This is an **individual assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

Project2 is due November 13 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/514422/assignments/6245733) in the Canvas assignment.

## Dataset - Ships Dataset

The dataset you will be working with is available in Canvas under [Files/Project 2 - Ships Dataset](https://ufl.instructure.com/files/89513968/download?download_frd=1).

## Edit this READ-ME

Please edit this read-me file with information about your project. There are no requirements for this readme file, but you can find a [template here](https://github.com/catiaspsilva/README-template).

### Files for submission:
1. training ipynb and pdf files
2. test ipynb and pdf files
3. Project2_report file
4. requirements.txt - environment file. To create a copy of same environment, use "pip install -r requirements.txt".
5. Updated Readme.txt file-contains the list of files for submissions and links to download dataset and pickle models.

### Models list from the gdrive link:
1. model1_rf.pkl - Pickle file for Random forest classifier with all features
2. model2_rf.pkl - Pickle file for Random forest classifier with dimensionality reduction via PCA
3. model3_rf.pkl - Pickle file for Random forest classifier with dimensionality reduction via ISOMAP.
4. model1_lr.pkl - Pickle file for Logistic regression classifier with all features
5. model2_lr.pkl - Pickle file for Logistic regression classifier with dimensionality reduction via PCA
6. model3_lr.pkl - Pickle file for Logistic regression classifier with dimensionality reduction via ISOMAP
7. model1_dt.pkl - Pickle file for Decision tree classifier with all features
8. model2_dt.pkl - Pickle file for Decision tree classifier with dimensionality reduction via PCA
9. model3_dt.pkl - Pickle file for Decision tree classifier with dimensionality reduction via ISOMAP
10. test_data.pkl - Pickle file for test data obtained after train test split.

### Instructions to run training and test. ipynb files
1. Create a folder named 'ships_dataset'.
2. Download the dataset from given link and store ship_data.npy, ship_labels.npy files and scenes folder inside 'ships_dataset' folder.
3. Create a folder named 'project2_models'.
4. To use already trained models, download the model files from the link: https://drive.google.com/drive/folders/15oyxDd-Utaqg9_UQ2Z7fegdn5Yh94fu6?usp=sharing and upload all the models in 'project2_models' folder.
5. If training new models, store the new pickle files in the 'project2_models' and use this folder to test the models.
6. Use the environment from 'requirements.txt' file to set up the same environment conditions of Jupyter notebook.
7. Use 'UFRC Python-3.10' kernel.

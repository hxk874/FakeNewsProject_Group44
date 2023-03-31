# Fake News Project - Group 44

The authors are Project Group 44: Ellen, Isak, and Tove. 

This repository contains the code for the exam project in the Data Science Class at UCPH for block 3, 2022/2023.
- Modelling.ipynb 
- Evaluation.ipynb

Since GitHub doesn't accept files larger than 25 MB, large datafiles and saved models are uploaded in google drive, and can be downloaded from here: 
[Google Drive](https://drive.google.com/drive/folders/1IlzLLjC91VWXk47Z4oNbRCpK-oPjfYsV?usp=sharing)

Please download and unzip the files in the drive folder, and add them locally in the repository on your machine, if you wish to run the code. 

It is not advised to run the full "Modelling" notebook, since the training of the advanced model runs for a significant amount of time. To see model performances, access "Evaluation" after downloading the data and the saved models from google drive. The Evaluation-notebook must import the cleaned datafile, '600K_cleaned.csv', the models saved in the .joblib-files, and the LIAR data in the .tsv-files to run, so make sure to have these downloaded locally to run the notebook. 

Furthermore the folder "Other" contains files used under processing the data. 
- process_1mil.ipynb
- process_2mil.ipynb

To run the processing files, you will need to download the entire Fake News Corpus (avaliable [here](https://github.com/several27/FakeNewsCorpus)), and add it locally to your repository. The cleaning of the data might also run for several hours, so only do this if you have a lot of time allocated! 

The process_1mil.ipynb creates a csv-file necessary for running a code-block in process_2mil.ipynb, and must thus be run first. 



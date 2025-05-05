# Read Me

### Environment Used:
`Python 3.13.3 .venv`

### Imports:
Running the `installDependencies.ipynb` file should cover all potential libraries used in the project.

### Models:
6 Class Emotion Model -----> `ser_stacking_emo.pkl`

3 Class Mood Model -------->  `ser_stacking.pkl`

### Example Usage:
`ModelTestFile.ipynb`

### Feature Sets:
6 Class Emotion Feature Set -----> `librossa_features_emo.csv`

3 Class Mood Feature Set --------> `librossa_features.csv`

Third Block in `798FeatureExtraction.ipynb` has a bool called `dataSet` that controls which set it generates

### Data Sets
The data sets were too large to include in the .zip and github repo. Here are the links to where you can download them.

`RAVDESS` ----->
`https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio`

`SAVEE` ------->
`https://www.kaggle.com/datasets/barelydedicated/savee-database`

`EMODB` ------->
`https://www.kaggle.com/datasets/piyushagni5/berlin-database-of-emotional-speech-emodb`

In theory it shouldn't be hard to modify the feature extraction function to accept audio instead of paths if you want to send it audio from a mic and get some test data. I unfortunately ran out of time to give it a try.

### Pre Splitting Data
If you would like to pre-split your data before it goes to any models then `split_data.ipynb` is an easy way to do that. Just make sure to chnage any names so you don't accidentally overwrite something.

### Notes:
- Please reach out if you have any questions.
- I have some other files I did not include, but they are mostly random models I tried once or never managed to get working.
- Files in the `BinaryMetaAttempt` folder have not been run in quite some time and may need some finicking to get working properly.
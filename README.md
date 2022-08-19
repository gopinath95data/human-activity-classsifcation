# Human-Activity-Classsifcation

Human Activity Classification by Smartphone & Smartwatch Sensors :running_woman: :standing_woman: :climbing_woman:

:purple_circle: This project is based on the data from WISDM Lab of Frodham University, NY - available from the UCI Machine Learning Repository
https://archive.ics.uci.edu/ml/datasets/WISDM+Smartphone+and+Smartwatch+Activity+and+Biometrics+Dataset+

:purple_circle: Note: This model specifically uses only the smartwatch accelerometer readings of the users since it would represent the hand motions of the users. A more robust, complex and accurate model may be built by combinig the accelerometer and gyroscope readings from both the smartphone and smartwatch

### File and Folder description

raw_data - contains raw gyroscope and acceleromter readings from smartwatch and smartphone from 51 participants. In this project only the raw processed data in the subfolder "raw" is used.

full sequence data - contains extracted data from 51 partiipants classified into their actions. Each sequence from a single user contains 3200 readings for 17 actions.

:file_folder: final data - the final train and test data for the model 

:file_folder: raw_data_preprocess.ipynb - preprocess raw data into full sequences categorized by actions

:file_folder: generate_data - extract data as a specific sequence length and given number of samples
    :pencil2: tunable params:
        sequence length: 80 in current model
        samples per target: 200 in current sample



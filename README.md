# GRAB Driver Safety
We compare several models to detect wether the GRAB driver is safe or not.
<br> <br> <br>
There are 3 Main Process that will be applied in this case :<br>
1. Data Preparation and Preprocessing
2. Modelling Comparison
3. Hyperparameter Tuning
4. Metrics Evaluation for the fix Model
<br>
<br>

The dataset that will be used are 10 drivers dataset and label dataset.<br>
Steps of our data processing are :
- Import all datasets
- Concate 10 driver datasets become single main dataset as dataframe
- Get Information about Dataset (Like some missing value, size of table, metadata, etc)
- Make Some Feature Engineering that consist Adding new features to dataset
- Aggregate the dataset by 'bookingID' variabel with Mean
- Merge 'label' dataset to the main dataset
- Cleaning Dataset
  - Avoid redundant
  - Missing Value Checking

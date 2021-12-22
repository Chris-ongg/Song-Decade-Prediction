Folder Tree:
-Final Report.pdf
-Milestone 1.ipynb
-Milestone 2.ipynb
-Preprocessing for Milestone 2.ipynb
-Extra models (NNs and SVM).ipynb
-requirements.txt
-README.txt
-data/
---data.csv*
---data_by_year.csv*
---data_by_artist.csv*
---data_by_genres.csv*
---data_w_genres.csv*
---useful_data1.csv
---recleaned_data_stdscle.csv
---recleaned_data_stdscle_v2.csv
---recleaned_data_stdscle_v2_wartists.csv
---cleaned_data_wo_artists
-individual notebooks/

See DETAILS for file descriptions

Note: * this means that the files were obtained from the Kaggle source.

********************************************************************************************************************************
********************************************************************************************************************************

Kaggle source (dataset has since been updated to include more info): https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks

NOTE: All plots and sections in the final report will reference the relevant code location.

********************************************************************************************************************************
********************************************************************************************************************************
DETAILS:

1. "Milestone 1.ipynb" is the file that represents the 
      bulk of work done for Milestone 1.

2. "Milestone 2.ipynb" is the file that represents the 
      bulk of work done for Milestone 2/Presentation.

3. "Preprocessing for Milestone 2.ipynb" contains the code 
      used to standardize all the numbers and to perform
      final preprocessing.

4. "Extra models (NNs and SVM).ipynb" contains the NN 
      and SVM code.

5. data/ contains all the diffferent versions of data created and used across all notebooks

6. individual notebooks/ contains all the notebooks that were used to create the 4 main notebooks

data/
1. All versions of the recleaned_data_stdscle*.csv have been passed through a standard scaler. In v1, we passed every feature through the scaler. 
   In v2, we avoided passing the one-hot-encoded values into the standard scaler (since it is redundant). 
   v2_wartists includes the artist information for later analysis. All these variants can be generated via the Preprocessing for Milestone 2.ipynb notebook.

2. data.csv, data_by_artist.csv, data_w_genres.csv, data_by_year.csv, data_by_genres.csv are all provided via kaggle.

3. useful_data1.csv contains data with only the genre information present. It is generated in Milestone 1.ipynb as a part of Section 4.

4. cleaned_data_wo_genres.csv contains data that was cleaned with genre data removed (since we decided against a recommender after consultation). 
   This .csv is the product of the code steps in Milestone 1.ipynb Section 1.

individual notebooks/
This folder contains a selection of the major notebooks that were used in the code (in original form).

Note: Please use the requirements.txt with conda.

********************************************************************************************************************************
********************************************************************************************************************************


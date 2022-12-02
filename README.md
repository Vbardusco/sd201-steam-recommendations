# sd201-steam-recommendations

This project aims to create a recommendation algorithm for video games based on Steam games info.

We recommend to check the notebooks in parallel of following the report to have examples and the precise code.

Description of the files:

- final_report.pdf : the report of the project

kaggle_dataset:
- recommendation_algorithm.ipynb : the final notebook to test the algorithm with your steam ID (please follow the tutorial inside)
- data_preparation.ipynb : the notebook showing our data cleaning process
- knn_progress.ipynb : the notebook showing the progression to make a recommendation algorithm based on K-Nearest-Neighbors and the evaluation of this algorithm
- fis_progress.ipynb : the notebook showing the progression to make a recommendation algorithm based on Frequent ItemSets and the evaluation of this algorithm
- svd_knn.ipynb : the notebook showing the progression on improving the knn-based algorithm with SVD

custom_dataset:
- get_data_set.ipynb : the notebook showing the scraping process to create our own dataset
- data_preparation.ipynb : the notebook showing our data cleaning and analysing of the custom dataset
- knn.ipynb : the notebook showing our knn-based algorithm used with the scraped dataset

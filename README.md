# Book-Recommendation-Systems



## Goal
The goal of this project is to make a recommendation system which will recommend the user a book, based on the search results given input by the users.


## Dataset
The dataset which is used here, is collected from Kaggle website. Here is the link of the dataset : https://www.kaggle.com/jealousleopard/goodreadsbooks. I have uploaded the same in [`Dataset`](https://github.com/abhisheks008/ML-ProjectKart/tree/patch-45/Book%20Recommendation%20Systems/Dataset) folder too, you can access that!


## What Have I done?
1. Importing all the required libraries. Check [`requirements.txt`](https://github.com/abhisheks008/ML-ProjectKart/blob/patch-45/Book%20Recommendation%20Systems/requirements.txt).
2. Upload the dataset and the Jupyter Notebook file.
3. Data Description
4. Data Processing
5. Data Visualization
6. Outliers Handling
7. Machine Learning Models
    - KNN
    - t-SNE
    - DBSCAN
8. Testing the models
9. Conclusion

**************************************
## Libraries used
|Numpy|Pandas|Matplotlib|Sklearn|Seaborn|XgBoost|isbnlib|
|-|-|-|-|-|-|-|
|progressbar|copy|scipy|mpl_toolkits|newspaper|tqdm|
************************************



## Conclusion
* **Clustering** is the best way to represent this project.
* we have deployed three different types of clusters, such as, **KNN**, **t-SNE** and **DBSCAN**.
* After deploying all the algorithms, we have seen that more or less all the models are showing **similar results**.
* Hence, to develop the recommendation system one can use **any of the three algorithms** used here.
* But, using **DBSCAN algorithm** provides the user better experience in terms user data given, so I will recommend to use DBSCAN algorithm over the KNN and t-SNE clustering.
* DBSCAN Model is having the accuracy of **92.56%**.
*******************************


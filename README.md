# Amazon-Review-Text-Mining

In this task, our goal is to predict the rating score (an integer out of 1, 2, 3, 4, 5) given only the Amazon review text. In other words, we will try to capture the customer's overall satisfaction about the product from the review text that he/she wrote. We will explore diverse types of preprocessing raw text data into a format that can be provided to machine learning models. More specifically, we will try several bag-of-words models to represent the Amazon review text and examine which type of representation of the text yields the best predictive performance.

For the data, we will be using the Amazon reviews on movies and TV ranging from May 1996 to July 2014. Here is the dataset source: http://jmcauley.ucsd.edu/data/amazon/. The original dataset contains information about 1697533 reviews.

Note: The data-related files (original dataset json file, pickle files and scipy sparse matrix npz files that are loaded during the work) are not uploaded here due to their large sizes. But the Jupyter Notebook file contains all the code (commented) used for creating (and saving) those files.



[Dataset citations]
- Ups and downs: Modeling the visual evolution of fashion trends with one-class collaborative filtering \
R. He, J. McAuley \
WWW, 2016

- Image-based recommendations on styles and substitutes \
J. McAuley, C. Targett, J. Shi, A. van den Hengel \
SIGIR, 2015

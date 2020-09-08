This text file is walk-through of the data science part of our project:

1. We used https://411.ca/business/search?q=accessories%20retail%20toronto%20on for scrapping the data. 
2. The code for this can be found in data_scrapping_cleaning1.ipynb notebook.
3. The clean csv file was created called clean_sb_version1.csv which creates the names of the stores, their address and postal codes.
4. We got the lat/long coordinates from the postal codes
5. We clusted based on kmeans using the lat/long coords
6. In the future, we will refine the clustering algorithm as well as add in the clustering based on type of store, store demographic etc.
# Overview
Co-created with Shelby Stall over the course of a DePauw Data Mining course from Jan '26 to May '26.

# Download
Ensure that dataset is downloaded into personal google drive before using.

# Project Abstract
What determines whether a book becomes a bestseller—and how long it remains one—remains an open question in publishing. 
While traditional sales prediction models rely heavily on historical sales data, reader sentiment and qualitative feedback are often overlooked. 
This project investigates which book attributes are most strongly associated with bestseller status and duration by integrating reader reviews with bestseller 
list data, including author frequency. Using datasets from Goodreads and the New York Times Bestseller list, we extract attributes such as genre, ratings, and emotional 
sentiment from user reviews. Textual data is processed using Term Frequency–Inverse Document Frequency (TF-IDF) and a Vector Space Modeling (VSM) to identify similarities 
among highly rated books. We then apply Truncated Singular Value Decomposition (SVD) to detect patterns in attributes and ratings, incorporating weighted metrics to emphasize 
characteristics linked to longer bestseller duration. Finally, we use OLS and KNN regression models to predict how long a book remains on the bestseller list based on features 
such as debut rank, publisher, author, average numerical review, and review sentiment. Unlike prior research focused primarily on sales prediction, this study directly compares 
reader sentiment with past bestseller performance to estimate book duration on bestseller lists. Differences between first-time authors and returning authors were examines with 
OLS and KNN models as well. Results, evaluated using $R^2$ and RMSE, suggest that qualitative book attributes do not exhibit a strictly linear relationship with success. 
Overall, this work offers insight into how reader feedback and book characteristics align with bestseller outcomes and examines differences in duration for first-time 
versus returning authors, creating potential applications for publishers and authors.

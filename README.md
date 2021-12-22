# Data Source and Information
### The [Amazon](http://deepyeti.ucsd.edu/jianmo/amazon/categoryFilesSmall/Software_5.json.gz/) dataset contains the customer reviews for all listed Software products spanning from May 1996 up to July 2014. There are a total of 12169 reviews.

# Attribute Information![bokeh_plot(2)](https://user-images.githubusercontent.com/40862259/147097460-cfafe5a7-95d4-4bc7-89d3-df1554798992.png)


    asin - Unique ID of the product being reviewed, string
    vote - number of votes, int32
    image - NaN or Not Available
    verified - whether the user is verified or not, string
    overall - The reviewer's rating of the product, int64
    reviewText - The review text itself, string
    reviewerID - Unique ID of the reviewer, string
    reviewerName - Specified name of the reviewer, string
    summary - Headline summary of the review, string
    unixReviewTime - Unix Time of when the review was posted, string
# Objective
### We have given a review and we have to identify whether a review is good(rating of 4 or 5) or bad(rating of 1, 2 or 3).

# Classification of Reviews
### The following algorithms were used:
*   Gaussian Naive Bayes
*  Decision Tree Classifier
* Random Forest Classifier

### The report can be accessed from [here.](https://drive.google.com/file/d/1syKxsey1uXdG4mgB117-bLgd8PSTNBmS/view?usp=sharing)

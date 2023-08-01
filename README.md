"# Movie-Recommendation-System" 
The Movie Recommendation System is an intelligent application designed to suggest personalized movie recommendations to users based on their preferences and viewing history. Whether you're a movie enthusiast or just looking for something new to watch, this system will help you discover exciting films that match your taste.

## Features

This is an item-based collaborative filtering system using MovieLens Datasets. 

I have trained a KNN model to cluster similar movies based on user's ratings and make movie recommendation based on cosine similarity score of previously rated movies.

## Learnings

The key takeaway for me in this project was the Long Tail Property.

The distribution of ratings among movies often satisfies a property in real-world settings, which is referred to as the long-tail property.


According to this property, only a small fraction of the items are rated frequently. Such items are referred to as popular items. The vast majority of items are rated rarely. This results in a highly skewed distribution of the underlying ratings.

While dealing with large amount of customer response data, we should always check if it follows the long tail property.

Neglecting this can result in a biased prediction or an inaccurate conclusion due to the sparsity of data.

## Results

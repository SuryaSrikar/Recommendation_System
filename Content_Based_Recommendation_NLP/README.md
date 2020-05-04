# Movie Recommendation System

This repository contains the code for building movie recommendation engine.

## Details about Dataset

 All the information related to dataset is described in this section.

## Dataset
* We have used MovieLens dataset in order to build movie recommendation engine. 
* You need to download dataset from [this link](https://drive.google.com/drive/folders/1JnQXDCsGAb75I4PRRMDHUO0WxmXT-usv?usp=sharing)
* Put dataset inside `input_data` folder. 


### Types of dataset

1. **The full dataset:** This dataset consists of 26,000,000 ratings and 750,000 tag applications applied to 45,000 movies by 270,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags.
2. **The small dataset:** This dataset comprises of 100,000 ratings and 1,300 tag applications applied to 9,000 movies by 700 users.
3. We will build a simple Recommendation for movies using **The full dataset**.


### Data description
* It contains 100004 ratings and 1296 tag applications across 9125 movies. These data were created by 671 users between January 09, 1995 and October 16, 2016. This dataset was generated on October 17, 2016.

* Users were selected at random for inclusion. All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

* The data are contained in the following files.
```
credits.csv
keywords.csv
links.csv
links_small.csv
movies_metadata.csv
ratings.csv
ratings_small.csv
```
 
More details about the contents and use of all these files is given in README.txt

### Download dataset 
In-case, there is need to download dataset then use either of the given links.
* If you wnat to download MovieLens dataset hosted on Kaggle then use [this link](https://www.kaggle.com/rounakbanik/the-movies-dataset/data)
* If you want to download MovieLens dataset from its official website then use [this link](https://grouplens.org/datasets/movielens/latest/)


### List of other dataset

* MovieLens - Movie Recommendation Data Sets [link](https://grouplens.org/datasets/movielens/)
* Netflix Prize Dataset [link](http://academictorrents.com/details/9b13183dc4d60676b773c9e2cd6de5e5542cee9a)
* Yahoo! - Movie, Music, and Images Ratings Data Sets [link](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r)
* Cornell University - Movie-review data for use in sentiment-analysis experiments [link](http://www.cs.cornell.edu/people/pabo/movie-review-data/)
* MovieTweetings - [link](https://github.com/sidooms/MovieTweetings)



##### Install dependencies using conda

```
nltk:             In-built installed with anaconda
numpy:            In-built installed with anaconda
scipy:            In-built installed with anaconda
scikit-learn:     In-built installed with anaconda
scikit-surprise:  $ conda install -c conda-forge scikit-surprise
Pandas:           In-built installed with anaconda
matplotlib:       In-built installed with anaconda 
seaborn:          In-built installed with anaconda
jupyter notebook: In-built installed with anaconda
                  In-built installed with anaconda
jupyter lab:      In-built installed with anaconda
textblob:         $ conda install -c conda-forge textblob 

# Text Mining of Yelp Reviews

The Yelp dataset provides data for business and the interactions with their customers through reviews. These reviews include information about the business, the user, the review, and the rating, among others. The goal of this project is to create a predictive model that allows to predict the rating (good or bad) a user has given to a business based on the review itself.

* **Import libraries**: CountVectorizer, TfidfVectorizer

* **Preprocess the data**
  * dummy code column "rating"
  * process the "review" text
  * create and build a TF-IDF and bigrams (n-grams = 2) set and the original attributes. 
* **Create a new model using the new features**: decision tree, AUC

* Find **common words** in good/bad reviews
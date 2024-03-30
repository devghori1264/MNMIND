# Movie Recommendation System
# Content-Based Movie Recommendation System -
This type of recommendation engine works on the concept that if a user liked a particular movie, he/she might like a movie similar to it based on attributes such as genre, director, actors etc.

# Similarity Score -
How does it decide which item is most similar to the item user likes? Here come the similarity scores.

It is a numerical value which ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

# Cosine Similarity -
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.


# IDE's used -
1. Jupyter Notebook
2. PyCharm Community Edition 2022.1.1

# Dependencies -
pandas

numpy

scikit-learn

nltk

ast

streamlit

requests

streamlit_lottie

pickle

pip


# How to run the project?
1. Clone or download this repository to your local machine.
2. Run the movie-recommender-system.ipynb python file on your Jupyter Notebook by installing all the required libraries.
3. Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt in PyCharm. 
4. Get your API key.
5. Replace YOUR_API_KEY in (line no. 18) of web_app.py file and hit save.
6. Open your terminal/command prompt from your project directory and run the file web_app.py by executing the command streamlit run web_app.py.
7. And Hurray! That's it. Your Recommendation Engine is ready!

# Deployment method -
Deploying using Heroku Git from Heroku CLI

Step-1 Download and install the Heroku CLI.

Step-2 If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

$ heroku login

Step-3 Clone the repository

Use Git to clone APP NAME source code to your local machine.

$ heroku git:clone -a APP NAME

$ cd APP NAME

Step-4 Deploy your changes

Make some changes to the code you just cloned and deploy them to Heroku using Git.

$ git add .

$ git commit -am "make it better"

$ git push heroku master

# Features -
1. It saves time of user by just taking movie name as input and recommends five most similar movies to the user.
2. It can in additional take feedback from the user about the modifications that can be done.
3. It also has an introduction section for the user to learn.
4. It can further be extended to rate the movies.

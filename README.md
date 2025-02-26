# Real-time-Sentiment-Analysis-for-Customer-Feedback-project-using-Python-Flask-MongoDB-and-Docker
This project is a Flask-based RESTful API that performs real-time sentiment analysis on customer feedback. It classifies text as positive, neutral, or negative using NLTK's Vader Sentiment Analyzer. The results are then stored in MongoDB for further analysis.  

Install Python and Flask:

pip install flask pymongo textblob

Install MongoDB (You can use a MongoDB cloud service like MongoDB Atlas or set up a local MongoDB server).


Install TextBlob:

pip install textblob


Run MongoDB: If you're using a local instance of MongoDB, start it by running:

mongod

Create a requirements.txt:

flask
flask-pymongo
textblob

Build the Docker image: In the project directory, run the following command to build the Docker image:

docker build -t sentiment-analysis-app .

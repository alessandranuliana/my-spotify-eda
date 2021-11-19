# FYI:

This little work is an Exploratory Data Analysis on my Spotify data.

- Currently I have been using my personal data. I request it to Spotify to perform some data analysis regarding most listened genres, songs, etc.
- I'm using Spotify API to fetch some details that are not available on my own data - or maybe it are, but I want to know how I could work with APIs for data analysis purposes and I find this project could be a motive to do it.
- This project is just for me polishing some data analytics, visualization and data science concepts and practice. 

The reference used and which inspired both this project and my ideas are [here](Docs.md). 

# Project Organization:
_This is under development yet. I update as I work on it._

[data/](data): Here is some clean data I've generate to make easier the analysis and the imports. It was generated using the data provided from Spotify and it's related to my streaming history. 

[Analysis01](Analysis01.ipynb): Here I perform a first analysis trying to get some info about my streaming history regarding genres and artists most listened during this past year.

[ProcessAndFetch](ProcessAndFetch.ipynb): This is where I organize the data coming from the API and fetch with the data available from my streaming history. 

[AnalysisVisualization](): I'm currently working in how to visualize the data analised in the previous notebooks.


# If you want to try it:

- You have to create an `.env` file with these following credentials:
```
USERNAME = "Your user"
CLIENT_ID = "Your client id"
CLIENT_SECRET = "Yout client secret"
REDIRECT_URI = "http://localhost:7777/callback" 
```

The first three values you obtain from an spotify account you have to get in order to be able to grasp the data. If you are already an user, you can register on the spotify developer api using the same account. 
The redirect uri I used as [[2]]([5]) used (if I'm not mistaken). It's just a callback to when you connect with spotify to request the data, it will return this was a successful request. There are other ways to do it (connect to request) without using the callback (like oauth, for instance). But you can use this value I used if you want. 

You have also to install the requirements in an environment for this project:
 ```
 python3 -m venv env
 source env\Scripts\activate - if you're using Windows
 pip install -r requirements.txt`
  ```
		

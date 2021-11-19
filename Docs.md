# Spotify Docs:
- [Requests Examples](https://developer.spotify.com/documentation/web-api/reference/#endpoint-get-users-saved-tracks)
- [Scopes/Endpoints](https://developer.spotify.com/documentation/general/guides/scopes/)
- [Console Request Example](https://developer.spotify.com/console/get-current-user-top-artists-and-tracks/?type=artists)
- [Dashboard](https://developer.spotify.com/dashboard/)

# References
[[1]](https://towardsdatascience.com/get-your-spotify-streaming-history-with-python-d5a208bbcbd3) [[2]](https://towardsdatascience.com/visualizing-spotify-data-with-python-tableau-687f2f528cdd) [[3]](https://jovian.ai/abode118/spotify-data-prep) [[4]](https://medium.com/@rafaelnduarte/how-to-retrieve-data-from-spotify-110c859ab304) [[5]](https://engineering.atspotify.com/2015/03/09/understanding-spotify-web-api/) [[6]](https://stmorse.github.io/journal/spotify-api.html) [[7]](https://veekaybee.github.io/2020/02/25/secrets/)

# Libs
- [Spotipy](https://github.com/plamere/spotipy)

# How to run:

- You have to create an .env file with these following credentials:
USERNAME = "Your user"
CLIENT_ID = "Your client id"
CLIENT_SECRET = "Yout client secret"
REDIRECT_URI = "http://localhost:7777/callback" 

The first three values you obtain from an spotify account you have to get in order to be able to grasp the data. If you are already an user, you can register on the spotify developer api using it. 

The redirect uri I used as [[2]]([5]) used. You can use this value. You have also to install the requirements in an environment for this project:
 ```
 python3 -m venv env
 source env\Scripts\activate - if you're using Windows
 pip install -r requirements.txt`
  ```
		
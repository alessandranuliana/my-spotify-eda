# *E*xploratory *D*ata *A*nalysis on my Spotify data

If there's something I like is music. I'd listen every minute if I can. And I also love discover new songs based on the ones that make me feel _good_ (the definition of good is subjective, and depends of the mood).
From that pointed, I also love data, and joining these two things, I decided make something fun and kinda of hard: try to see if I have a pattern based on my listen history on Spotify. But I wanna to go deep. I want to know if I have a spectral distribution that is like _the one_ for me - and here I joined signal processing, other subject that i dont love so hard, but I'm learning find it fun. I'm not interested here on recommender songs using my data (although this will be probably a future work), but rather try to get the audio features elements to find a pattern about the kind of songs that i like the most, at the moment.

But to get on that point, I'm starting with the basics. I'm fetching Spotify API to get my on data, limited to 50 samples so far. Then transforming them into a handy csv file to after visualizing my momentary data.
And only after that the games begin, by trying to get the songs samples from the preview url that Spotify gives on the responses when hiting the API. 

On the Docs.md I have the basics reference that I've been using work on this personal project (:
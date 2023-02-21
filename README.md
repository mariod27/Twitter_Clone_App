# Twitter_Clone_App

About 

This is a minimized clone of the Twitter application - a micro-blogging platform.

Rather than building the entire application, the purpose of this project is to build out a functioning CRUD API for the Twitter clone app via the Flask web framework. 

This application utilizes a three-tier architecture where the user will make a request to the web server and will then retrieve a result from the database. Since this project mainly focuses on backend development, I use the Insomnia client to check what a front-end client (web browser) would see from interacting with the web server. This is done by sending HTTP requests via the Insomnia client and implementing collections of endpoints in the tweets.py and users.py files.  

Therefore, the Insomnia client will send an HTTP request to the Flask server, which uses SQLAlchemy ORM to query the twitter database in the Postgres server and retrieve the result set. The Flask server then returns an HTTP response to the Insomnia client which then displays the response.  

The main endpoints that were created in the tweets.py file include Tweets Index, Show Tweet, Create Tweet, and Delete Tweet.

Within the users.py file the endpoints are Users Index, Show User, Create User, Delete User, and Update User. 

There are also additional endpoints called Liking Users and Liked Tweets. Liking Users returns a list of users who like a specific Tweet and Liked Tweets returns a list of tweets that a specific user has liked. 


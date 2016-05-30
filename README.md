# SmartShuffle_debug_app
debug apk for trying out the application

This application queries all the songs found on your device and SD card, and lets you listen to them on shuffle mode. 

While you listen to your favorite songs and skip those you don't want to listen to, the application learns which songs you are 
more interested in and assigns a higher importance to them. This importance factor is used to determine the probability of a song
being selected out of the whole list. The user can also set the importance or "rating" for any song manually. 

The application modifies the rating of each song based on the factors below: 

-if a song was completed

-the moment a song was skipped (earlier corresponds to lower rating) 

-user manually updating the rating 

The application menu allowes the user to see their songs in a list, update the settings, and quit the application. 

The settings menu allowes the user to set the behaviour of the app as follows: 

-Enable looping

-Pause music on minimize

-Pause music when headset is disconnected

-Set the sort order for displaying the song (Note: app must be restarted for this change to take effect)
-Reset song ratings 

*in development: backup the ratings in a separate file 

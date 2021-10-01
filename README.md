<<<<<<< HEAD
Hello New Line New Change 
Project Team Members: Logan Chayet
=======
=======
Project Team Members:
Jordan Wood
Clay Fricke
Logan Chayet
Jack Higgins
Preston 
>>>>>>> ea6f956cf202ad821d56cb649a4bf38755aa3c2c
blah blah blah main branch

Application Description:

Mobile app available to the public that can be used to transfer playlists to Spotify from Apple Music and vice versa. Of the large group of people that listen to music daily, there is a pretty even split between spotify and apple music. A big part of listening to music is sharing it with people you know, and as such, there is no reputable way of quickly and effectively transferring music between the platforms. Whatsmore, both platforms are competitive enough to the point that there is no official method of transferring playlists between the two platforms.

To fix a problem most people have encountered numerous times, we have decided to make an app that allows users to transfer playlists between the two platforms and only have to sign into one of them. Many solutions that already exist are complicated and require signing into both platforms. This is because these websites are intended to be used when the user is switching from one platform to the other and needs to transfer their private playlists. Our app would solve this problem but also give the user the ability to save other peoples playlists from other platforms with ease.

Application Architecture:

The user accesses the application and transfers their playlist to a universal playlist type. Playlist gets sent to another user who opens it within their app and creates the playlist within their account on their music listening app. Uses Spotify and Apple Music APIs which have the functionality to create playlists and get songs from playlists. 
User interface will be done in swift. Python for connecting the front end to the APIs.

User may also search for playlists from both platforms whilst in the app and or paste the direct link to the playlist to start transfer. All songs can be transferred on device and saved to a playlist created by us as an exact duplicate. The user will then be redirected to the new playlist where they can listen/save.

Swift is used in IOS, Java is used in Android. Do we want a multi-OS app?
API for Python.
https://apple-music-python.readthedocs.io/en/latest/
https://spotipy.readthedocs.io/en/2.19.0/

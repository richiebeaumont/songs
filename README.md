
Don´t forget to change the cache versions in the cache data and push to origin in the github. 


# Instructions

**You need to do these steps once:**

1) Install [GitHub Desktop](https://central.github.com/deployments/desktop/desktop/latest/win32)

2) Open the program

3) Log in with your GitHub account

4) Add the 'songs' repository to your Desktop

**You need to do these steps to update the images:**

1) Make sure the images are JPEGs and end with `.jpg`

2) Copy the files into `Desktop/songs/`

3) Rename the files to `1.jpg`, `2.jpg`, etc

4) Open `Desktop/songs/cache.appcache` with notepad

5) Update the file to list all the `.jpg` images

**Important:** Make sure this list matches exactly or it won't work offline

6) OPEN THE CACHE FOLDER IN THE SONGS FOLDER Update the file's version number (add 1)

7) Commit with a message and 'Push to origin'

8) Open 'Songs' on your iPad with an internet connection

9) Wait 2 minutes then close the app

Done. The app should now work with WiFi switched off.

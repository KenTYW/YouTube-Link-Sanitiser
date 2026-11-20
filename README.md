# Link Sanitiser
YouTube and Twitter/X/Xhitter puts trackers into their share links. This 3 line Python code lets you get rid of it instantly. 

## For the python (.py) file ##
1. To use, get a python IDLE, e.g. on Android, Pydroid 3.

2. Run the python file, paste in your link and press enter.

3. The link is now sanitised, enjoy your cleaned link.

## For the JSON (.json) file ##
### To Install ###
1. Get the HTTP Shortcuts app on Android via this link: https://f-droid.org/packages/ch.rmy.android.http_shortcuts 

2a. Click this link to auto import: https://http-shortcuts.rmy.ch/import?url=https://github.com/KenTYW/YouTube-Link-Sanitiser/raw/refs/heads/main/shortcut.zip

2b. Alternatively, download the JSON file here. Within HTTP Shortcuts, tap the 3 dots on the top right of your screen. Click Import / Export and find the json file and click it.

3. Success, you have now imported the shortcut! Congratulations!

### To Use ###
1. On any social media, tap the SHARE button

2. Find your installed shortcut in the share menu (might be hard to find the first time as Android has to learn you want to use this app)

3. A new share menu should pop up. This is intended behaviour. The new share menu now contains the sanitised link, freely share knowing that you are now clean.


#### How it works ####

* It splits the link by the "?" and gives back the front part of the link, which is the actual video link

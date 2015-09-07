Chrome Scripts
---

I often want to change a small thing on webpages by writing a quick script.  But in order to get these scripts to run every page load I have to write a chrome content script with an extension, and a manifest.json, etc, etc.  It's a lot of work just to have a small script run every page load.

This extension allows for you to write small scripts that run each page load.  All you have to do is define some URL that will match the script, and then write the script.

This allows for simple things like removing annoying elements from sites with javascript or making the enter key submit a form instead of send an enter character.


###Installation

1. Clone this repo
2. Go to chrome settings -> extensions -> enable developer mode
3. Press load unpacked extension
4. Locate the cloned repo
5. Enjoy


###Screenshot

![ScreenShot](http://i.imgur.com/UGmV9MP.png)
This will alert the page you're browsing assuming you're on a page that matches `https://github.com/*`.

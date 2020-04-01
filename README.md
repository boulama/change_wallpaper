![alt text](https://media.giphy.com/media/dX9YEwekcWC46DAit4/giphy.gif "Littel animation of how it works")
# change_wallpaper
So, I woke up this morning and I looked at my Mac's wallpaper thinking that it's been there for a while and I needed to change it... Therefore I headed over to Unsplash... Where I spent over 30 minutes just looking for a wallpaper. Needless to tell you that I didn't find any that suit me.
I decided to code a simple script that would go there, and pick a randmon wallpaper for me and set it on my desktop. Now this script runs anytime I start my laptop and I start my day with a new, fresh wallpaper 😌.

This is a simple script that allows you to change your wallpaper from the terminal using bash &amp; osascript thanks to the amazing pictures gotten from the Unsplash API.
### First get your own unsplash API key:

[Click here to get an Unsplash API key](https://unsplash.com/developers)

Once you have your API key, head over to the `key.sh` file in order to add it and you can now call the script to change your Wallpaper.
``sh change_wallpaper``

In the script ``change_wallpaper.sh``, here is the syntax of the ``change_wallpaper`` function:

```
change_wallpaper <theme> <size>
```
``<theme>`` is used as the query parameter (if you want images of planes, nature, etc...).

``<size>`` is the different sizes allowed by the unsplash API:
* raw -> full size images (~18 Mb)
* full -> full size (~5 Mb)
* regular -> medium size (~1 Mb)
* small -> small size (~300 Kb)
* thumb -> thumbnail (~100 Kb)

Feel free to fork it and edit as you wish.
Come talk to me on Twitter [@boulama_k](https://twitter.com/boulama_k)

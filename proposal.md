# Proposal

## What will (likely) be the title of your project?

PiTunes

## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A Raspberry Pi interface that data on my weekly Spotify listening

## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?

The software will be a GUI that is displayed on the Pi 24/7, showing my top 3 songs and top 3 artists of the last week. Each week it should refresh (and display a refresh/loading screen in this process). The script can just be run directly from the Pi and won't need any further setup. Ideally, I would store each week's data in some kind of file or database. A CSV on the easier end, or a SQL configuration on the more advanced end. 

## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A

## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

N/A

## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

* A displayed list of top 3 artists of the last week
* A displayed list of top 3 songs of the last week
* A weekly refresh

### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

* A nicely designed GUI
* Images for artists / cover art for songs
* Having it actually work seamlessly on the Raspberry Pi with a display (not just that it works when I run it on my laptop)

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

* A nice refresh screen
* A way to store the data each week

## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

The first and most important step is to get Python to interact with my Spotify and the songs I listen to. This can be done with the LastFM API, as the LastFM service itself already tracks Spotify listening. I think there exists a Python package that comes with built in functions for the LastFM API. Unfortunately, the documentation is not the greatest (there is barely any at all) so I might have to rely on reading the source code to figure out how to actually use it. The other problem is that the LastFM API does not provide any album artwork, so once I get it working, I will have to find a workaround to get the album artwork for the songs I extract from my listening data. After that, the next thing to do is design the actual GUI to display everything, likely using Tkinter.  

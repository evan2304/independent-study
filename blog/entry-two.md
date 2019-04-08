# Blog Entry Two: Getting into the basics

## Now that I chose EarSketch! 🥇

Once I commited to EarSketch as my topic, the path I was going down became clearer. As I delved into the topic I felt reassured that I chose what was right for me. 

## Vocab is always key. 🔑

#### ... about the workspace
As I started reading the curriculum provided by EarSketch in greater detail, I realized that I was going to have to learn the assosciated vocab to progress. The EarSketch curriculum provides lessons on the various vocabulary that you need to be familiar with and the continues by referencing these words. 

First things first, get to know the various areas of the workspace. 

**Sound browser:** where you search for audio clips and can add your own files. *Located in the top left corner.*

**Scripts browser:** where your different code "files" are saved. Since EarSketch uses Python and Javascript, these "files" are called scripts. *Click on the folder with { } on it to access.*

**Share browser:** where you can see scripts that have been shared with you. *Click on the folder below the Scripts browser to access.*

**API browser:** here you can learn about all the possibilities with every EarSketch function.*Located under the share browser.* 

**DAW:** stands for Digital Audio Workstation and in general those are softwares where you can create music. In EarSketch this where you see the general overlook of the song you have created. *Located at the top of the page center.* 

**Code Editor:** this looks pretty familiar from previous code learning and is where you type the code in your scripts.*Located in the center of the screen.*

**Console:** basically displays the status of the code that you are running. *Located below the code editor.*

#### ... about the DAW

**Playhead:** the red line

**Transport controls:** contains the reset, play/pause, mute, volume, loop and toggle mushroom (allows you ta click and play a beat over your current track.)

**Measure numbers:** musical measurement unit that depend on the tempo set in the script. 

**S/M buttons:** silence / mute that specific track. 

#### ... about the script setup

**1. Comments section:** typically at the beginning and is the script description. Includes script name and author. 

**2. Setup section:** <br>
`from earsketch import *` - adds the EarSketch API <br>
`init(some_value)` - initalizes the DAW <br>
`setTempo(some_value)`sets the tempo for the script. 

**3. Music section:** where your actual code for the sounds goes.

**4. Finish:** every script must end with `finish()`

## Creating my first script! 💃🏽

After creating an account, I clicked the `+` in the code editor to create a new script. I have decided to learn python so I named the file test.py and began coding. 

1. Add `fitMedia()` between `init()` and ``setTempo() in the setup section.
2. Keep cursor between the parentheses of `fitMedia()` and pick a clip to insert in the Sound Browser by clicking the paste button. E.g. `fitMedia(RD_TRAP_BASSDROPS_1)`
3. The next step is to determine where the clip should be placed (its track number) and how long it should last (start and end point). Easy way to remember: `fitMedia(clipName, trackNumber, startMeasure, endMeasure)`
4. Press run and play!

At first when I tried step 2 and ran the code right away, I got the following error message:<br>
`Error message >> TypeError: There is an error with the expected data type, fitMedia() takes exactly 4 argument(s) (1 given) on line 13 Click here for more information.`

This error message luckily was not hard to decipher, so I could immeditely tell that I had missed 3 arguments. Upon reading further, I learned that I of course has to place the clip somehwere. 

## What I created. 👣

I played aroud a bit with different sounds and plugged in different arguments for a trial run. Click
[here](https://earsketch.gatech.edu/earsketch2/#?sharing=xTMn6_3HXfCf45b8jKesFg) to hear my first attempt. Click Run and Play. 

## Takeaways. 👩🏽‍💻
**Slow and steady wins the race.** After spending a long time reading through instructions, and basic set up (which was not all that intriguing), I was starting to feel impatient. I tried jumping ahead but realized that I had skipped too many steps. I had to back track and make the concious effort of being patient so I could eventually get to a place where I could tinker and create my own sounds. 

#### Resources I used:
[EarSketch](http://earsketch.gatech.edu/landing/#/) <br>
<br>
[Back to Content](../README.md) 
|
[Back to Entry One](entry-one.md)

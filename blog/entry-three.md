# Blog Three: Keep learning

### A little more learning ...✍🏽

At the beginning of this week I felt like I had learned a lot the past week, but still hadn’t solidified all of these concepts. So I decided it would be a good idea to go back and take some of the quizzes at the end of each chapter, so see how much information I had in fact retained.
 
#### ... about music 🎤
**Beats:** the most basic unit of measurement in music <br>
**Tempo:** beats per minute (bpm) <br>
**Measures:** consist of the same number of beats <br>

#### ... about coding 👩🏽‍💻 
**Syntax errors:** code breaks the rules of how the code should be organized <br>
**Runtime errors:** your script runs but stops due to an issue <br>
**Logic errors:** the script runs in a way that you didn't expect <br>

### NEW FEATURE 🆕
**`setEffect()`**: like adding a filter on a photo, but for audio!!! When using this, you must have four parameters (track, effect type, effect parameter, value)<br>

**track:** you would type the number of the track you want it to apply to (number from 1-5) <br>
**effect type:** one of the effects listed in the API browser.<br>
**effect parameter:** the setting of the effect. E.g. if the effect type is VOLUME the effect parameter could be GAIN. (essentially increasing the volume.<br>
**value:** the value the parameter should increase or decrease by.<br> 

**Sometimes you don't want to apply the effect to the whole track!** If that is the case, you can uses envelopes!

**envelopes:** use value-time pairs to pinpoint where the effects will differ from the other parts of the track. e.g. (-50, 1, -5, 6) -> a point is places at measure 1 at -50 decibels and another point is places at measure 6 at -5 decibels. A smooth transition then happens between these points. 

*NOTE:* dB value can be between -60 and +12

If you choose to use an envelope, this is what the syntax would look like: `setEffect(track, effect type, effect parameter, value, envelope start value, envelope start measure, envelope end value, envelope end measure)`

[Here is an example where I used an envelope!](https://earsketch.gatech.edu/earsketch2/#?sharing=FbJOmjgfa8lLAQdun3yPng
) Click Run and then Play. 
### Takeaways. 👌🏽

**Test yourself!** When you are learning so many new things at once, especially if it involves a lot of new vocabulary, it is helpful to spot check yourself! See how much you remember of the things you learned earlier. Luckily on the EarSketch platform, there are short quizzes at the end of each chapter. During this week, and moving forward, I went back and did some of those quizzes again.


[Back to Content](../README.md) 
|
[Back to Entry Two](entry-two.md)



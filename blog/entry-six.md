# Blog 6: makeBeat( ) and Loops
This week I continued learning more technical aspects of making music. As I have learned more and more about music, I have started to apply what I learn when I am listening to music. It's so cool to me that I can break down some songs that I listen to because I can identify some of the transitions etc. that are used. 

### General information about computers... 💻
**Primary memory** also referred to as RAM (Random Access Memory) houses data and instructions temporarily. On the other hand, **secondary memory** holds large amounts of data for a long time even when the computer isn't on. The **CPU** (Central Processing Unit) interacts only with the (primary) memory. 

### ... and how that general information relates to EarSketch 👂🏽
When one records audio on the computer, it is stored in the CPU. When you want to access that sound by pressing play, the CPU fetches the data and sends it as an output to the speaker. 

When you upload a sound to EarSketch, the CPU converts the data to a .wav sound file that is sent to the EarSketch server (external server). The EarSketch servers CPU then saves the file on the secondary storage for long time safe-keeping. 

### makeBeat( ) and Step Sequencing 🥁
This is completely different from what I've been doing before! makeBeat( ) uses a process called step sequencing to compose music "note by note." 

#### Familiar coding concepts 🥳
makeBeat( ) uses **strings** to define beats. Each  character refers to a "sixteenth note sub-beat" of a measure. Here is an example: `myDrumBeat = "0-00-00-0++0=0"`  where 0 starts playing a clip, - means rest and + lengthens the clip into the next sixteenth sub-beat. 

*Remember the syntax!* 
1. Clip Name
2. Track Number
3. Measure Number (starting measure)
4. Beat String 

[Click here for my example](https://earsketch.gatech.edu/earsketch2/#?sharing=lm2Nf8-eCkDMF1XI7U4dXw) Click Run and then Play. 

### But how do I keep it going? Loops! 🔁
Now that I have learned how to make a beat, how do I keep it going without copying and pasting lines of code?

**For-Loop:** lets the computer know to repeat a section. 

`for i in range(2):`

**Loop Body:** statements that will repeatedly execute (indented after the colon)<br>
**Loop Counter:** variable used as loop counter <br>
**Range:** list of numbers for the loop to "count through". It takes two arguments: startingNumber and endingNumber. 

[Click here for the use of a for-loop on my previous beat](https://earsketch.gatech.edu/earsketch2/#?sharing=Vl3OIlXC2ZkkAKZorfubZQ)

### Takeaways. ✍🏽

**Apply what you learn!** I think it is great to apply what you learn in the classroom, to "real world cases." It helps put into context why you are learning and reveals the deeper nuances of every subject. "In the real world" the case may not be as straightforward as they are when you study the topic, and that just results in more learning!

[Back to Content](../README.md) 
|
[Back to Entry Five](entry-five.md)
|
[Next](entry-seven.md)


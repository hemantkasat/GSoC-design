				Rhythm Ruler Design
Below diagram represents an rough instance of Rhythm Ruler:->

![alt tag](https://raw.githubusercontent.com/hemantkasat/GSoC-design/master/RhythmRuler/Rhythm-Ruler-Design.png)
It consists of play, close, export button and a button to choose beat instrument. It represent a whole note divided into 3 notes with different note value, 1st and 2nd of note value 4 and 3rd of note value of 2.This three notes are represented in three different dissection with their musical notation.
For choosing the division value we can think of a prompt that will pop up when we click on any dissection and by filling the division value we will be able to divide the dissection into further parts.

Now if we export the instance into Music Blocks code we can think of this way :->


This blocks in the rhythm ruler blocks gives us the instance represented above.

An another option can be we make a new block as we know number of notes will be same (1) in all the rhythm blocks so we can make a new block that take only one argument note value use it instead of the available rhythm block.

The difference between pitch time matrix and rhythm ruler is, in matrix the rhythm is fixed and we choose different pitches for different beats. In Rhythm Ruler we choose the duration of different beats and for each beat the sound(pitch) is same with a particular instrument.

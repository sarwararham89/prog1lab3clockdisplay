Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.
Question 21: its set to 0 because its connected to the Numberdisplay which its Value is 0.
Question 22: it says 00:00
Question 23: You have to increment it 60 times so that it turns into 1:00, since in the SourceCode the NumberDisplay minutes is set to (60). 
Question 24: NumberDisplay digit = new NumberDisplay(10) 
Question 25: Rectangle window = new Rectangle(int height , int width); 
{ 
   window.setValue(heigth);
   window.setValu(width);
} 
Question 26: The second is where you can put your custom Value, hour and minute in which it would start. 
Question 27: Similarities: 1- same assignments for hours and minutes in both Constructors . 2- visibiity modifier. Differences: 1- in the parameters of the second "public ClockDisplay(int hour, int minute)" and the first "public ClockDisplay()". 2- in the first Constructor, we can see the last statement being different from the second Constructor. 
Question 28: 

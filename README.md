# butter


## insiration
<<img src="https://static.wikia.nocookie.net/rickandmorty/images/6/67/Butter_Robot_Picture.png/revision/latest?cb=20171106225602" width="400">

i really enjoy watching rick and morty and when i was thinking about something to do for a project i tought how cool it would be the make the butter robot.


## planning
<<img src="https://github.com/maxtimmins/butter/blob/main/Screenshot%202021-02-12%20at%2019.46.38.png?raw=true" width="400">

this is the first model ive made in onshape of our project.
<<img src="https://github.com/maxtimmins/butter/blob/main/Capture.PNG?raw=true" width="400">

this a is a draft of where i think we might want the arduino.


this week I worked on trying to make my vision a reality. I learned that what I designed isnt intirerly what I was going to make. I learned this when I had to re design my base to fit the new wheels.


```C++
/*

*/

void setup() {
//drive to the butter//

//bend over//

//widen arms//

//close arms around butter//

//bend back up//

//drive to destination//

    
}

void loop() {
    
}

  }
```
I got the servo to move with some simple code (see below)
```C++
#include <Servo.h> //Include the servo library
Servo servoblue; //The servo gets the name “servoblue”
void setup()
{
servoblue.attach(8); //The signal line of the servo is on pin 8
}
void loop()
{
64 
;servoblue.write(90); //Position 1 with an angle of 0°
delay(1000); //Wait 3 seconds
servoblue.write(90); //Position 2 with an angle of 90°
delay(1000); //Wait 3 seconds
servoblue.write(90); //Position 3 with an angle of 180°
delay(1000); //Wait 3 seconds
servoblue.write(-90); //Position 4 with an angle of 20°
delay(1000); //Wait 3 seconds
}
```

The IR sensor has been quite a challenge and I still need to work on that but I think I have made good progression with understanding the IR sensor.

Got help from Mr. Helmstetter with the wiring diagram since I was quite confused about it (see below)
<img src="https://github.com/maxtimmins/butter/blob/main/Screenshot%202021-03-16%20at%2012.26.49.png?raw=true" width="400">
The project is going good but kind of slow, I do not believe we are on time. The IR sensor is very hard to figure out.
When I return from spring break to the lab I will be working on finishing up code and assembling. Avery
When I return from spring break to the lab I will be working on assembling. Max

<img src="https://github.com/maxtimmins/butter/blob/main/Capture2.PNG?raw=true" width="400">
this is the a redisng of the head mr helmstetter did to reduce cost and improve the look.
<img src="https://github.com/maxtimmins/butter/blob/main/Capture4.PNG?raw=true" width="400">
this is the finished design in onshape we are currently in the process of printing and constructing it, we had a bit of a blunder and all of our code was lost which we are working on correcting.
<img src="https://github.com/maxtimmins/butter/blob/main/Capture3.PNG?raw=true" width="400">
this is a rework of our original base where the shaft was connected here the shaft is printed seperate. 

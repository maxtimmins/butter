# butter


## insiration
<<img src="https://static.wikia.nocookie.net/rickandmorty/images/6/67/Butter_Robot_Picture.png/revision/latest?cb=20171106225602" width="400">

i really enjoy watching rick and morty and when i was thinking about something to do for a project i tought how cool it would be the make the butter robot.


## planning
<img src="https://github.com/maxtimmins/butter/blob/main/Screenshot%202021-02-12%20at%2019.46.38.png?raw=true" width="400">

this is the first model ive made in onshape of our project.

<img src="https://github.com/maxtimmins/butter/blob/main/Capture.PNG?raw=true" width="400">

this a is a draft of where i think we might want the arduino.


this week I worked on trying to make my vision a reality. I learned that what I designed isnt intirerly what I was going to make. I learned this when I had to re design my base to fit the new wheels.

## code

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

```C++
// IRremote - Version: Latest 
#include <IRremote.h>


 /* 
  IR Receiver Demonstration 1
  IR-Rcv-Demo1.ino
  Demonstrates IR codes with IR Receiver
  Displays results on Serial Monitor
 
  DroneBot Workshop 2017
  http://dronebotworkshop.com
*/
 
// Include IR Remote Library by Ken Shirriff
#include <IRremote.h>
 
// Define sensor pin
const int RECV_PIN = 4;
 
// Define IR Receiver and Results Objects
IRrecv irrecv(RECV_PIN);
decode_results results;
 
 
void setup(){
  // Serial Monitor @ 9600 baud
  Serial.begin(9600);
  // Enable the IR Receiver
  irrecv.enableIRIn();
}
 
void loop(){
  if (irrecv.decode()){
    // Print Code in HEX
        Serial.println(results.value, HEX);
        irrecv.resume();
  }
}
```
This is the code that pulls the HEX values of the buttons pushed off the remote so we can apply them into our code in the future.

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

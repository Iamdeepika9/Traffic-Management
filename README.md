# Traffic-Management
Density based traffic management system built using Arduino, IR Sensors and IoT

![img1](https://github.com/Iamdeepika9/Traffic-Management-/assets/96690780/4dc8890c-5ee5-4220-a449-9411160c6664)

## Objective of the project :
1. Our project aims at reducing traffic congestion and unwanted long time delay during the traffic light switch overs especially when the traffic is very low.
2. It is designed to be implemented in places nearing the junctions where the traffic signals are placed, in order to reduce the congestion in these junctions.
3. It keeps a track of the vehicles In each road and accordingly adjusts the time for each traffic light signals.
4. The higher the number of vehicles on the road the longer will be the time delay allotted for that corresponding traffic light signal.

## Components Used :
 1. Arduino UNO board
 2. IR sensors
 3. Red and Green LED’S
 4. 220 ohms resistors
 5. Jumper Wires
 6. Bread board

## Working :

![img2](https://github.com/Iamdeepika9/Traffic-Management-/assets/96690780/c705c464-94fc-40e9-9c30-71686417ecc6)

1. The heart of this circuit is an Arduino, which is connected to four IR sensors measuring the number of vehicles passing through the four lanes. During the first 10 seconds, all the vehicles passing through the lane is measured which is then processed and accordingly delays are set. Thus, the road with more vehicles is shown green light for a more duration which makes it possible for efficient traffic control
2. This project uses an Arduino Uno as a microcontroller. Arduino gets its four inputs from IR sensor which are set so that they receive signals from vehicles coming towards the road. The IR readings are logged into the Arduino memory for the first 10 seconds. After the initial 10 seconds, the readings are compared to set levels so that the output delay for LED is calculated. This happens for every of the four main control lines for the signal output.
   
## IR Sensor Module :

![img3](https://github.com/Iamdeepika9/Traffic-Management-/assets/96690780/b217351e-3935-4db2-b833-45e9e58d265c)


The IR sensor module includes five essential parts like IR Tx, Rx, Operational amplifier, trimmer pot (variable resistor) & output LED.
 1. VCC Pin is power supply input
 2. GND Pin is power supply ground
 3. OUT is an active-high o/p

In this we are using infrared sensors namely infrared transmitter and infrared receiver .the IR transmitter sends light ray to IR receivers. If there is any obstacles occurring between these two then the data signal is send to microprocessor and its act upon a signal.

## Block Diagram :

![img4](https://github.com/Iamdeepika9/Traffic-Management-/assets/96690780/fe0246ba-c9af-446c-a7d6-a6b66b1252de)


## Conclusion :
1. Thus from above theory we can conclude that using the method of density based control of traffic lights we can save a considerable amount of time and also we can prevent excessive traffic jams thus leading to smooth traffic flow.
2. In practice presently in India we are following time based control of traffic signals and we are experiencing a heavy traffic jams all over which in turn consumes lot of time and fuel. We hope these methods will be adopted as soon as possible so that the limitations we are experiencing with present method can be overcome.






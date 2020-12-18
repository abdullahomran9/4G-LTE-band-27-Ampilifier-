Until now even though we reached 5G the coverage of 4G still not that good on some locations, or even for some campers and nature lovers who go camping they can not stay connected to the world.
What I have in my mind is a small cellular amplification kit, that can be deployed easily and run with low power 5V chargers or battery banks.
I did a rough block diagram of the project and already started doing the Schematic for the repeater, with 4G network and band 28 to be exact.
I will share my progress here.

# Block Digram 
This is a simplified block diagram to explain the basic conscept behinf the amplifier . 
![](https://cdn.hackaday.io/files/1714857336814240/Block Diagram.JPG)

# DETAILS
Just finished the first version of the Schematics and PCB design . 

yet i think the PCB need some review do to many reason , firstly because i lack experience in PCB Deign , secondly is that this is RF PCB, so there is some guidelines to follow. 

This PCB is design foe OSHPARK 4 layer pcb . 

I followed the common rules of RF PCB designs :
1. Use 50 Ohm Traces ( OSHPARK 4 Layer Stack ) . 
2. Curve the RF traces or use slanted corners . 
3. 4 layer PCB .

some others i didnt follow : 

I used 0805 SMD components , because it is easier to solder. 
did not pay attention to the stub pads of smd components on the RF trace. it spouse to increase gradually until it reach the right size 

![](https://cdn.hackaday.io/images/6201281589145384815.JPG)

Finally this is a 3D view of the PCB . and i will attach a Schematic and update the Block Diagram. 

![](https://cdn.hackaday.io/images/9466951589145385273.JPG)
![](https://cdn.hackaday.io/images/9992131589145513809.JPG)

I can refer any one who is interested in RF PCB to watch Micheal Ossmann YouTube video about RF circuit Design. 

# Full Schematics
![](https://cdn.hackaday.io/files/1714857336814240/0001.jpg)

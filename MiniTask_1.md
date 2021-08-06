# Mounted HUD - Project Pipeline and Ideation

## Project statement:

This project aims to create a helmet mounted HUD system to assist the bike riders navigate the roads by projecting the city map onto the screen. 


## Pipeline:
1. The first stage of this project involves identifying the components needed for the project.
2. The next stage of the project is to analyse each of these components, their pros and cons, and decide which components can be worked on and improved. 
3. The next stage is the ideation phase, in which reasearch is done on the previously identified components to improve their performance. During this phase, extensive market research is also performed and pre-existing solutions are also reviewed and ideas are borrowed from them. 
4. After this, the components are finalised and ordered, the design plans made, and the code to control the various components is written. 
5. Now the prototOype can be built, assembled and debugged.
6. Finally, the project can be taken further for more R&D.

### Analysing each phase:
#### 1. Components identification:
The components used for this project are:
1. Microcontroller
2. PCB
3. HUD display
4. Bluetooth connection transmitter/reciver

#### 2. Project mechanism:
Phone App --> Bluetooth Transciever --> Microcontroller --> HUD display
#### 3. Part of pipeline to break:

|Part of the Pipeline | Feasibility | Advantages | Disadvantages |
| --- | --- | --- | --- |
|Microcontroller|It is difficult to modify this without expertise in manufacturing microcontrollers|It is low-cost, easily programmable and versatile with pre-built functions|It is not a computer and there are limits to the activities that it can perform|
|PCB|Can be easily designed based on requirements|They are low cost and easy to design. |Difficult to modify once manufactured|
|HUD display|The display itself cannot be changed but there are several different types of displays to choose from|||
|Bluetooth tranceiver|Easy to use SPP;widely used also|Low powerconsumption. Betterrange than IR. Cheapin terms of cost.|Low bandwidthcompared to WIFI.Short rangecommunication|
|Andriod App|Hard to code an app|Can be customised precisely to the requirements|Security might be an issue|

From the above table, it is clear that the PCB, transciever and the HUD can be modified. While the Android app also needs to be coded, the task comes in the domain of the PDC team of the project. 

##### Transciever 
The transciever should have a range of atleast 4 feet, should be inexpensive and as small as possible. Based on market availability, an HC05/06 transciever should work and costs around 600-1000 rupees. The currently available options on the market are by DSD Tech, Electrobot (Rs 750, 400 after discount), Omatom Power (Rs 300), etc. T

##### Display
For the display, we have several options that can be implemented. The display can be either LED or LCD based. Furthermore, the display can be either transparent so as to show images/ maps without interfering without obstructing the view of the road, or can be projector based, with the LED/ LCD projector projecting the image onto a transparent screen. For the former, the currently available options on the market, such a those by sparkfun, crystalfontz, etc. However, the major disadvantage of such a display setup is that such OLED screens are expensive with most market options costing upwards of 500 rupees. Furthermore, the resolution of these screen is low and create the issue of forcing the rider to continously refocus between the road and the screen and the road. The last issue can be resolved by using optics and ensuring an infinity focus. Thus, a projector system would be preferable. The currently available options include . The next issue that has to be taken care of is the optics system. The optics setup must ensure that the image is formed at infinity so as to ensure seamless integration of the image projected with the road. <View the various current solutions from task 2>


##### PCB 

The pcb is easy to design using any freely available software and is inexpensive to make. The major design parameter that must be optimized is to ensure that the pcb is as small as possible so as to consume less space. 

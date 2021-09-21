# STM32H743VIT6_Boring_TECH_QSPI
 STM32H743VIT6 Boring_TECH QSPI Sources
 
 
 !***.stldr CubeProgrammer External Loader***!
 STM32CubeIDE to build .stldr file (I use 1.7.0)
 
 I took this project as an example to create the .stldr file. : https://github.com/manoloaterol/MCUDEV_DevEBox_H743-W25Q64-EL
 
 And very useful video . If you are going to create your own .stldr file you should watch. : https://youtu.be/XqCq0xtQmbI
 
 The two boards have the same MCU and FLASH, but each board's FLASH is connected to different pins. So the .stldr file in that project(DevEBox) will not work in Boring_TECH.
 
 
 Copy the .stldr file into CubeProgrammer\bin\ExternalLoader\
 
 When you run CubeProgrammer, you can find it in External Loaders(EL) with the name W25Q64-STM32H743VI
 
 
![alt text](https://github.com/osos11-Git/STM32H743VIT6_Boring_TECH_QSPI/blob/main/CubeProgrammer%20ExtLoader/CUBEP.JPG?raw=true)
![alt text](https://github.com/osos11-Git/STM32H743VIT6_Boring_TECH_QSPI/blob/main/CubeProgrammer%20ExtLoader/CUBEP2.JPG?raw=true)



 !***Example***!
 
 Just a simple example. This example does not create a .stldr file. It communicates with the W25Q64 and handles operations such as read,write etc...
 

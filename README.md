# STM32H743VIT6_Boring_TECH_QSPI
 STM32H743VIT6 Boring_TECH QSPI Sources
 
 STM32H7 FW v1.9.0
 STM32CubeIDE v1.7.0
 STM32CubeProgrammer v2.7.0

 # ***Example1***
 
 Just a simple example. This example does not create a .stldr file. It communicates with the W25Q64 and handles operations such as read,write etc...
 
 Based on WeAct Studio H743VIT6 and some chinese source.
 
 WeAct Studio H743VIT6 : https://github.com/WeActTC/MiniSTM32H7xx/tree/master/SDK/HAL/STM32H743/06-SPIFlash_Test/Drivers/BSP/W25QXX
 
 Chinese Source : https://cloud.tencent.com/developer/article/1662643
 
Also quadspi.h , quadspi.c , main.h edited.
 
 
 # ***Example2***
 
 Just a simple example. This example does not create a .stldr file. It communicates with the W25Q64 and handles operations such as read,write etc...
 
 Based on Controllers Tech Youtube channel and GitHub, ST Official QSPI Driver for N25Qxx, DevEBox H743VIT6 and some chinese source.
 
 This example is based on the general similarity between the W25Qxx and the N25Qxx. In the project, ST's official N25Qxx drivers were edited for the W25Qxx.
 
 Controllers Tech Video : https://youtu.be/xIfh_uYy-OU
 
 Controllers Tech GitHub : https://github.com/controllerstech/STM32/tree/master/QSPI/N25Qxxx
 
 DevEBox H743VIT6 : https://github.com/manoloaterol/MCUDEV_DevEBox_H743-W25Q64-EL
 
 Chinese Source : https://cloud.tencent.com/developer/article/1662643
 
 This example is similar to the video on the Controllers Tech Youtube channel. 
 
 Also quadspi.h , quadspi.c , main.h edited.

 
 
 # ***.stldr CubeProgrammer External Loader***
 
 STM32CubeIDE to build .stldr file 
 
 I took this project as an example to create the .stldr file. : https://github.com/manoloaterol/MCUDEV_DevEBox_H743-W25Q64-EL
 
 And very useful video . If you are going to create your own .stldr file you should watch. : https://youtu.be/XqCq0xtQmbI
 
 The two boards have the same MCU and FLASH, but each board's FLASH is connected to different pins. So the .stldr file in that project(DevEBox) will not work in Boring_TECH.
 
 Copy the .stldr file into CubeProgrammer\bin\ExternalLoader\
 
 When you run CubeProgrammer, you can find it in External Loaders(EL) with the name W25Q64-STM32H743VI
 
![alt text](https://github.com/osos11-Git/STM32H743VIT6_Boring_TECH_QSPI/blob/main/Board%20Pics/board2.JPG?raw=true)
![alt text](https://github.com/osos11-Git/STM32H743VIT6_Boring_TECH_QSPI/blob/main/CubeProgrammer%20ExtLoader/CUBEP.JPG?raw=true)
![alt text](https://github.com/osos11-Git/STM32H743VIT6_Boring_TECH_QSPI/blob/main/CubeProgrammer%20ExtLoader/CUBEP2.JPG?raw=true)


 

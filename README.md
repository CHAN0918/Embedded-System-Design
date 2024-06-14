# Embedded-System-Design

For **Embedded_Assignment.c** file, it is the main.c file which is included in STM32CubeIde.

This respiratory is about the assignment.
This assignment is about the smart monitoring system that determine whether the day is suitable to drying the clothes.

Three sensors used:
1) Rain sensor: Detect the presence of water/raindrops.
2) Internal temperature sensor (included inside STM32 Nucleo Board): Calculate temperature by using suitable equation (pls check Embedded_Assignment.c (main.c) file for check details.)
3) Light Dependent Resistor(LDR): Detect the light intensity.

Internet of Things(IoT):
One of the IoT platform - ThingSpeak has been used for observe the data for this assignment.
Link(Public): https://thingspeak.com/channels/2403015 

Caution:
***Pls put all file into Core section***
1. For RingBuffer.h and ESPDataLogger.h (headers file), pls put inside **Inc** part.
2. For c files (UARTRingBuffer.c, ESPDataLogger.c and Embedded_Assignment.c(main.c) ) file, pls put in **Src** part.

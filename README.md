# Ultrasonic-Sensor Project

# Introdution
This project allows us to fully understand the importance of ultrasonic sensor characteristics. We use this ultrasonic sensor element to connect itself, and use the correct code to make it work properly. We will study the sensors and propose a list of important goals and test plans, conduct tests, collect and analyze data, and demonstrate.
# principle
The basic physical principle of ultrasonic sensor is that the sensor sends ultrasonic pulse and receives it back. Using the time difference between the transmitted signal and the received signal, the distance to the object can be determined. A common design is to build the transmitter and receiver into the same physical housing, although they can also be installed in separate units, such as some photoelectric sensors with separate transmitters and detectors.
# Connect the sensor
Vcc-5V; Trig-2; Echo-3; Gnd-Gnd
# Code
We can find it from the file Arduino code
# Testing process of static characteristics of ultrasonic sensor
In this project, we mainly test the static characteristics of linearity, sensitivity, range and stability. The measurement methods are the same. We can make a measurement and record the results. Then we can calculate and analyze the static characteristics we need. The method is use the plane book as a test object. The ultrasonic sensor is placed at a distance of 0 cm from the ruler, and the book is gradually away from the ultrasonic sensor. Start from 0 and move to 30 cm. 
# Measurement results and analysis
After the measurement in the previous step, we can get a lot of useful data, which can be found in all the files I released.
# Conclusion
The overall experimental process of ultrasonic sensing is relatively smooth. The static characteristics of this ultrasonic sensor are relatively ideal, but due to some limitations of the equipment, the range of the ultrasonic sensor is far from that in the ideal state. In a reasonable range, the input and output of the ultrasonic sensor are linear. At the same time, the sensitivity of the sensor is also very high. In addition, under normal temperature, the sensor has high stability and can work for a long time. However, it is not ruled out that the working stability of the sensor will be reduced under high and low temperatures. Assuming that the equipment is more precise, I think the sensor range will be better than the result of this experiment, and may be closer to the ideal state.

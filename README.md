# TEMPERATURE-MONITORING-SYSTEM-

*COMPANY* :CODTECH IT SOLUTIONS PVT.LTD

*NAME*:VIDHYARTTH S A

*INTERN ID*:CT04DH1668

*DOMAIN NAME*: embedded system

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTOSH

*DESCRIOTION*
The Temperature Monitoring System is a useful and practical electronics project that allows users to measure and monitor ambient temperature using a digital temperature sensor with Arduino. In this project, I used Tinkercad to simulate the behavior of a real-time temperature monitoring system. The main goal of the project is to read the current temperature using a sensor and display the value on an output device such as an LCD. This system is commonly used in smart homes, weather stations, and industrial automation where temperature tracking is required. In my simulation, I used the LM35 temperature sensor, which provides an analog voltage output directly proportional to the temperature in Celsius. The LM35 is connected to one of the Arduino’s analog input pins, typically A0. It outputs 10 millivolts per degree Celsius, so a temperature of 25°C would result in an output of 250 millivolts. The Arduino reads this analog voltage using the analog-to-digital converter (ADC) and converts it into a temperature reading using simple mathematical logic. To display the measured temperature, I used a 16x2 LCD connected with an I2C module, which simplifies wiring by using only two pins (SDA and SCL) connected to the Arduino’s A4 and A5 pins. In the simulation, I wrote a program to continuously read the analog signal from the LM35, calculate the corresponding temperature, and display it on the LCD. The system updates in real time, showing the current temperature with clear visibility. In a physical setup, this system could be further enhanced to include alerts such as turning on a fan or buzzer if the temperature goes beyond a certain limit. Since Tinkercad does not simulate heat or physical temperature changes, I used the sensor’s input pin to manually vary the analog signal, which mimics the behavior of changing temperatures. This allowed me to test and validate how the system responds to different conditions. This project also introduced the concept of analog sensors and how their output can be processed by a microcontroller to produce readable and useful data. It demonstrates important programming concepts like analog input reading, float variable calculations, and display interfacing. The Temperature Monitoring System also emphasizes power-efficient monitoring solutions and how such systems can be extended to include data logging or wireless transmission in advanced versions. It is a perfect beginner project for understanding how sensors and displays work together in embedded systems. Using Tinkercad as the simulation tool provides a safe, easy, and cost-free environment to experiment with the circuit and modify it without physical components. Overall, this project helps learners grasp essential concepts in sensor interfacing, analog-to-digital conversion, display communication, and decision-based output. It is ideal for students and hobbyists who want to get started with Arduino and build something practical that can be turned into a real-life temperature control or monitoring product in the future. The Temperature Monitoring System is not only educational but also a stepping stone toward building smarter and more interactive electronics systems.

*circuit*:

<img width="848" height="343" alt="Image" src="https://github.com/user-attachments/assets/4e674c78-0d58-4bfc-9f13-59f9bbe522b4" />

*output*:

<img width="870" height="435" alt="Image" src="https://github.com/user-attachments/assets/a9f4d234-c4be-40b3-a024-d5333e065ffa" />

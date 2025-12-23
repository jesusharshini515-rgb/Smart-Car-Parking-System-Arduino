# Smart Car Parking System (IoT – Arduino UNO)

## Project Overview
The Smart Car Parking System is an IoT-based application designed to automatically detect the availability of parking slots using sensors and Arduino UNO.  
The system helps reduce manual effort and improves parking efficiency by providing real-time slot availability.

## Technologies Used
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- LEDs (Red & Green)
- Embedded C / Arduino IDE

##  Working Principle
- The ultrasonic sensor measures the distance between the sensor and an object.
- If the measured distance is below a predefined threshold, the parking slot is considered **occupied**.
- If the distance is greater, the slot is considered **available**.
- LEDs indicate the slot status:
  -  Red LED → Slot Occupied
  -  Green LED → Slot Available

##  Components Required
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Red LED
- Green LED
- Breadboard
- Jumper Wires
- USB Cable

##  Circuit Connections
| Component | Arduino Pin |
|---------|------------|
| Ultrasonic VCC | 5V |
| Ultrasonic GND | GND |
| Ultrasonic Trig | Digital Pin 9 |
| Ultrasonic Echo | Digital Pin 10 |
| Red LED | Digital Pin 6 |
| Green LED | Digital Pin 7 |


##  Implementation
The Arduino continuously triggers the ultrasonic sensor to calculate distance using echo time.  
Based on the calculated distance, LEDs are controlled to reflect parking slot availability.


## Output
- Displays distance on Serial Monitor
- Red LED glows when a car is detected
- Green LED glows when the slot is empty


## 🚀 Future Enhancements
- Multiple parking slot detection
- LCD display to show available slots
- Integration with mobile or web application
- Cloud-based monitoring


## Author
**Harshini Gorle**  
B.Tech ECE, VNIT Nagpur  
📧 harshinigorle515@gmail.com  
🔗 LinkedIn: https://linkedin.com/in/harshini-gorle

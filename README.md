Smart Car Parking System

Project Overview  
The Smart Car Parking System is an Arduino-based automated parking management system designed to reduce manual effort and improve parking efficiency. The system detects vehicle entry, exit, and parking slot occupancy and automatically controls the gate while displaying real-time parking availability.

Technologies Used  
Arduino UNO  
IR Sensors  
Ultrasonic Sensor  
Servo Motor  
16×2 LCD Display  
Embedded C / Arduino IDE  

System Components  
- Arduino UNO as the main controller  
- IR sensors to detect vehicle presence at parking slots and exit  
- Ultrasonic sensor to detect vehicle entry  
- Servo motor to control the entry gate  
- LCD display to show real-time parking slot availability  

Working Description  
When a vehicle approaches the parking entrance, the ultrasonic sensor detects its presence. The Arduino checks the availability of parking slots using IR sensors placed at each slot.  
If slots are available, the servo motor opens the gate and allows entry. If the parking area is full, the gate remains closed.  
As vehicles occupy or leave parking slots, the corresponding sensors update the slot status. The LCD display continuously shows the number of available slots in real time.  
The system operates continuously and provides automatic gate control and slot monitoring without human intervention.

Features  
- Automatic vehicle detection at entry and exit  
- Real-time monitoring of parking slot occupancy  
- Automated gate control using a servo motor  
- Live display of available parking slots on LCD  
- Reduces manual supervision and traffic congestion  

Learning Outcomes  
- Understanding of embedded systems and microcontrollers  
- Hands-on experience with sensor interfacing  
- Real-time decision-making using Arduino  
- Integration of hardware components for automation  

Future Enhancements  
- Increase number of parking slots  
- Mobile or web-based monitoring  
- IoT cloud integration  
- Number plate recognition system  

Author  
Harshini Gorle  
B.Tech Electronics and Communication Engineering  
Visvesvaraya National Institute of Technology, Nagpur  
Email: harshinigorle515@gmail.com  
LinkedIn: https://linkedin.com/in/harshini-gorle

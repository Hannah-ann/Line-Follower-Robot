# Line Follower Robot 🤖

This is a mini-project using **Arduino UNO**, **IR sensors**, and **DC motors** to make a line follower robot.  
The robot detects a black line on a white surface using IR sensors and adjusts its direction using PWM motor control.

## 🧠 Code Overview
The code uses two IR sensors and two DC motors controlled through the L293D driver.  
The PWM frequency is increased for smoother low-speed motor control.

## 🧰 Components Used
- Arduino UNO  
- L293D Motor Driver  
- 2 IR Sensors  
- 2 DC Motors  
- Wheels & Chassis  
- Battery Pack  

## ⚙️ Working
- When both sensors detect white → move straight  
- When the left sensor detects black → turn left  
- When the right sensor detects black → turn right  
- When both sensors detect black → stop  

## 📷 Circuit Diagram
![Circuit Diagram](circuit_diagram.png)


## 📚 Learnings
- Embedded programming with Arduino  
- Motor control using PWM  
- Sensor interfacing  
- Real-time debugging

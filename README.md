# Automatic Door Sensor 🚪

A contactless automatic door system using an **ultrasonic sensor**, **servo motor**, and **Arduino** to open and close the door based on the distance of a person from the sensor.

---

## 🔧 Hardware & Software

- Arduino (Uno / Nano / similar)
- Ultrasonic sensor (HC-SR04)
- Servo motor (SG90 or similar)
- Jumper wires, breadboard, power supply
- Arduino IDE

---

## 🎯 Features

- Contactless door opening based on distance
- Adjustable distance threshold
- Smooth opening and closing using servo
- Simple and low‑cost implementation

---

## 🚀 How it works

1. Ultrasonic sensor continuously measures distance in front of the door.  
2. When an object/person comes closer than the set threshold, the servo rotates to **open** the door.  
3. After a short delay, the servo returns to the original position to **close** the door.  
4. Basic filtering is used to avoid random false triggers.

---

## ▶️ How to run

1. Open the `.ino` file in **Arduino IDE**.  
2. Select the correct **Board** and **Port** from the Tools menu.  
3. Upload the code to the Arduino board.  
4. Power the circuit and test by moving in front of the sensor.

---

## 📚 Learning outcomes

- Working with ultrasonic distance sensors  
- Controlling servo motors using Arduino  
- Basic real‑time embedded system design  
- Hardware–software integration

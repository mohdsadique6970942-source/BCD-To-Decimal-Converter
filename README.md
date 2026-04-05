# 🔢 BCD to Decimal Converter using IC 7447

This project demonstrates a hardware-based **BCD (Binary Coded Decimal) to Decimal converter** using the **IC 7447** and a **common anode 7-segment display**. It converts 4-bit binary input into a human-readable decimal output.

---

## 📌 Features
- Converts **4-bit BCD input (0–9)** into decimal display  
- Uses **IC 7447 decoder/driver**  
- Displays output on **7-segment display**  
- Simple and beginner-friendly digital electronics project  

---

## 🧰 Components Required
- IC 7447  
- Common Anode 7-Segment Display  
- 330Ω Resistors (7x)  
- 1kΩ Resistors (4x)  
- DIP Switch (4-bit input)  
- Breadboard / PCB  
- Connecting Wires  
- 5V Power Supply  

---

## ⚙️ Working Principle
The DIP switch provides a **4-bit BCD input** (A0–A3) to the IC 7447.  
The IC decodes this input and activates the corresponding segments of the 7-segment display to show the correct decimal digit (0–9).

---

## 🔌 Circuit Description
- Inputs A0–A3 are connected to DIP switches  
- Outputs (a–g) from IC 7447 connect to the 7-segment display  
- Current-limiting resistors protect the display  
- The display operates in **common anode configuration**

---

## 📷 Circuit Diagram
<img width="863" height="399" alt="image" src="https://github.com/user-attachments/assets/43ff427c-eb83-4a07-9e58-096d0f2263e9" />


---

## 🚀 Applications
- Digital display systems  
- Educational electronics projects  
- Basic calculator/display units  

---

## 🎯 Learning Outcomes
- Understanding BCD encoding & decoding  
- Working of IC 7447  
- Interfacing 7-segment displays  
- Practical digital circuit implementation  

---

## 📄 License
This project is open-source and free to use for learning purposes.

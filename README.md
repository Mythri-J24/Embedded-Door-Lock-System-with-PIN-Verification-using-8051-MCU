
# Embedded Door Lock System with PIN Verification using 8051 MCU

This project demonstrates a keypad-based electronic door locking system using the AT89C51 microcontroller, simulated in the Proteus environment. It integrates a 4x4 keypad for user input, an LCD for feedback, and a DC motor to simulate the lock/unlock mechanism, all programmed in Embedded C.

---

## 🔧 Features

- 4-digit PIN-based door unlocking
- LCD display for user feedback
- Motor control to simulate locking mechanism
- Error message on incorrect PIN
- Simulation and circuit diagram included

---

## 🧰 Components Used

- **AT89C51 Microcontroller (8051 Family)**
- **4x4 Matrix Keypad**
- **16x2 LCD Display (LM016L)**
- **L293D Motor Driver IC**
- **DC Motor (for lock simulation)**
- **12V Battery (Power Supply)**

---

## 📁 Project Structure

- `door_lock_simulation.pdsprj` – Proteus simulation file
- `circuit_diagram.png/pdf` – Circuit diagram of the system
- `door_lock_code.c / .asm` – Embedded C code for the microcontroller
- `README.md` – Project documentation

---

## 🚀 How It Works

1. User enters a 4-digit PIN using the keypad.
2. The microcontroller reads and compares it to a stored PIN.
3. If the PIN is correct:
   - LCD displays "Door Opened"
   - Motor activates to simulate unlocking
4. If incorrect:
   - LCD shows "Incorrect"
   - Motor remains inactive

---

## 🧪 Simulation

The entire circuit is simulated in Proteus, allowing testing of:
- Keypad input response
- Real-time LCD feedback
- Motor activation based on logic

---

## 📷 Screenshots

> *(Include screenshots of your Proteus simulation and circuit diagram here)*

---

## 📜 License

This project is for educational purposes and open to modification and reuse with attribution.

---

## 👨‍💻 Authors

- B Sai Swaroop  
- Mythri J  
- Ragavi M

---

## 🎓 Submitted as part of

**Microcontrollers and Applications (CSEN3021)**  
GITAM School of Technology, Bengaluru Campus  
April 2025

# RFID Access Door Lock 🔒

A security-enhancing RFID-based door lock system developed as part of our CSE project.

## 👨‍💻 Team Members

- **Dilip Meghwal**
- **Dilpreet Singh**

## 🧠 Problem Statement

Traditional door locking mechanisms, such as physical keys or passcodes, are prone to theft, loss, or unauthorized sharing—compromising security. A smarter, more secure solution is needed.

## ✅ Proposed Solution

We implemented an **RFID-based door lock system** where:
- Each user is assigned a unique RFID tag/card.
- Access is granted based on a secure, pre-defined list of authorized tags.
- The locking mechanism is controlled by a servo motor upon successful tag recognition.

This approach improves:
- 🔐 Security (eliminates key loss/passcode sharing)
- 🚪 Convenience (contactless access)
- 📈 Scalability (easy to add/remove users)

---

## 🔧 Hardware Components

| Component               | Purpose                             |
|------------------------|-------------------------------------|
| Arduino UNO            | Microcontroller unit                |
| RFID Reader (MFRC522)  | Reads RFID cards/tags               |
| RFID Tags/Cards        | User access identification          |
| Servo Motor            | Operates door locking mechanism     |
| HC-SR05 Ultrasonic     | Detects user presence               |
| Buzzer                 | Audible feedback                    |
| Jumper Wires & Battery | Power and connections               |

---

## ⚙️ Implementation Steps

1. Setup Arduino IDE environment
2. Install necessary libraries:
   - `MFRC522` for RFID
   - `Servo` for motor control
3. Wire up the hardware components
4. Write & upload the Arduino code
5. Test and calibrate the system
6. Assemble and mount the door lock system

---

## 💡 Learning Outcomes

- Hands-on experience with **RFID technology**
- Practical application of **Arduino programming**
- Interfacing **servo motors**, **buzzers**, and **RFID modules**
- Designing and debugging real-world **electronic circuits**

---

## 🐞 Challenges Faced

- Technical hurdles in RFID and hardware integration
- Debugging code errors and resolving library issues
- Troubleshooting faulty hardware connections

---

## 🎯 Future Enhancements

- 📋 Support for **multiple users** with different access levels
- 📈 Maintain **access logs** and send **notifications**
- 🔒 Enhance system with **biometric or keypad fallback**

---

## 📽️ Demo

A demonstration video is available.


# 📡 RFID Smart Attendance System (ESP8266)

An IoT-based smart attendance system that uses RFID technology to automate attendance tracking and store data in Google Sheets in real-time.

---

## 🚀 Features
- 📶 WiFi-enabled using ESP8266
- 🪪 RFID-based identification system
- 📊 Real-time data logging to Google Sheets
- 📟 LCD display for user interaction
- 🔔 Buzzer feedback on card scan
- ⚡ Fast and efficient UID processing

---

## 🛠️ Technologies Used
- ESP8266 (NodeMCU)
- MFRC522 RFID Module
- Arduino IDE (C++)
- Google Apps Script (Cloud Integration)
- Power Supply + Breadboard Setup

---

## 📌 How It Works
1. RFID card is scanned using MFRC522 module  
2. UID is read and matched with stored user data  
3. User name is displayed on LCD  
4. Buzzer gives feedback  
5. Data is sent to Google Sheets via HTTP request  

---

## 🔗 Project Structure
- `rfid_code.ino` → Main Arduino code  
- Google Apps Script → Handles data storage  
- Hardware setup → RFID + ESP8266 + LCD  

---

## 📊 Output
- Displays user name on LCD  
- Logs attendance (Name + UID + Timestamp) in Google Sheets  

---

## 💡 Future Improvements
- Add mobile app integration  
- Use secure HTTPS with certificates  
- Add face recognition for dual authentication  

---

## 👩‍💻 Author
**Alla Yasha Sri**  
📧 allayashasri@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/alla-yashasri-125294289/

---

## ⭐ Acknowledgment
This project was developed as part of IoT and embedded systems learning and demonstrates real-time cloud-connected applications.

# 🔥 Smoke Alarm Using Sensor

A cost-effective, IoT-ready smoke detection system built using the MQ-2 gas sensor and Arduino/NodeMCU. This project alerts users of smoke, LPG, methane, and other harmful gases via a buzzer and serial monitoring, offering early warning for potential fire hazards.

---

## 🚀 Features

- 🔍 Detects multiple gases: smoke, alcohol, LPG, methane, and propane
- 🔔 Buzzer alerts when harmful gas levels are detected
- 📊 Real-time data output via Serial Monitor
- 🌐 Easily expandable to IoT platforms (ESP8266 ready)

---

## 🧰 Components Used

| Component             | Description                          |
|----------------------|--------------------------------------|
| Arduino Uno / NodeMCU | Microcontroller board                |
| MQ-2 Gas Sensor       | Detects smoke/gases                  |
| Buzzer                | Emits alarm sound                    |
| PCB Board             | Circuit integration                  |
| Jumper Wires          | For connections                      |
| 9V Battery            | Power supply                         |

---

## 🧪 Working Principle

The MQ-2 sensor outputs analog values depending on the gas concentration in the environment. When the value exceeds a safe threshold, the system triggers a buzzer and logs the reading to the Serial Monitor. It's ideal for real-time smoke detection in homes and small industries.

---

## 💻 Arduino Code

The project code is written in Arduino C/C++ and can be uploaded via the Arduino IDE.

**[📂 Click here to view the code → `smoke_alarm.ino`](./smoke_alarm.ino)**

---

## 🗂 Project Files

- [`smoke_alarm.ino`](./smoke_alarm.ino): Main Arduino sketch
- [`mini_project.pdf`](./mini_project.pdf): Detailed project documentation
- Circuit diagrams and images (add them in `/images` folder if available)

---

## 📷 Images

> *(Add your circuit diagram, prototype photos, and screenshots here)*

---

## ⚙️ How to Use

1. Connect components as per your circuit diagram.
2. Upload the `smoke_alarm.ino` code to the Arduino/NodeMCU.
3. Open the Serial Monitor (9600 baud).
4. When gas is detected, the buzzer will sound.

---

## 🏁 Future Improvements

- 📱 Add SMS or email notifications using IoT
- ☁️ Log data to cloud (ThingSpeak, Firebase)
- 📲 Integrate with a mobile app for alerts

---

## 🧑‍💻 Authors

- S. Nandini (20NN1A04B6)  
- B. Nikitha (20NN1A0467)  
- M. Allabe (20NN1A0496)  
- R. Buela (20NN1A04B1)  
- K. Varshitha (20NN1A0485)  

Project guided by **Dr. S. Yallamandaiah**, Department of ECE  
**Vignan’s Nirula Institute of Technology and Science for Women**

---

## 📄 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).  
Feel free to use, modify, and distribute this code with proper credit.

---

## 🏷️ Tags

`#Arduino` `#MQ2` `#SmokeAlarm` `#GasDetection` `#IoT` `#EmbeddedSystems`

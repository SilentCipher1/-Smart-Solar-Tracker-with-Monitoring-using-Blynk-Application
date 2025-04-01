# -Smart-Solar-Tracker-with-Monitoring-using-Blynk-Application
This project is a dual-axis sun-tracking solar panel system with real-time monitoring to optimize energy efficiency. The system automatically adjusts the panel’s orientation to track the sun’s position, ensuring maximum solar power generation. Additionally, it features live performance monitoring via an IoT-based dashboard.  

🛠 Features
✔ Dual-Axis Sun Tracking – Adjusts horizontally & vertically for optimal sunlight exposure
✔ Real-Time Monitoring – Logs solar intensity, panel angle, temperature, and energy output
✔ IoT Integration – Sends live data to a cloud-based dashboard for remote access
✔ User Dashboard – View performance metrics via a web/mobile interface
✔ Automatic & Manual Control – Supports both auto sun tracking & manual override
✔ Energy Optimization – Increases solar efficiency and battery life

📌 Components List for Smart Solar Tracker with Monitoring
🔧 1. Microcontroller & Processing Unit
       ESP8266 And Arduino Nano – Controls motors, processes sensor data, and handles IoT communication.
![esp8266-nodemcu-wifi-module](https://github.com/user-attachments/assets/d50cffa9-582b-45bb-9249-381a3408e724)

🔆 2. Sensors & Data Collection
       Light Dependent Resistors (LDRs) x 4 – Detect sunlight intensity for tracking.
       ![download](https://github.com/user-attachments/assets/e4938ba7-e6a9-4a9f-aa5b-6a7732392b00)
       Resistors - 10K ohm x 4
       ![download (2)](https://github.com/user-attachments/assets/4d201859-8f95-4c98-81f3-3dd1998a62f0)
       Current & Voltage Sensor (INA219/ACS712) – Monitors power consumption.
       ![61wJ-KAxVEL](https://github.com/user-attachments/assets/8f3a2264-2a1c-4c3e-8562-2dbfe78b73e6)


⚙️ 3. Actuators & Motors
       Servo Motors x 2 (MG995 / MG996R / SG90) – For panel movement (dual-axis tracking). 
       ![download (2)](https://github.com/user-attachments/assets/0298b486-6157-49b8-bab6-a719fa9c5d2d)


🔌 4. Power Supply & Management
        12V Solar Panel (10W–50W, Based on Requirement) 
        DC-DC Step-Up/Down Module (XL6009 / LM2596) – Regulates voltage for components.

📡 5. Wireless Communication & IoT
      WiFi Module (Built-in Wifi) – Cloud communication.

📊 6. IoT Monitoring & Dashboard
      Blynk – Cloud platforms for real-time monitoring.


⚡ 7. Electronic Components & PCB
       PCB Board (Custom Designed or Perf Board) – Circuit integration.
   +   Voltage Regulators (AMS1117 / LM7805) – Provides stable voltage.
       Resistors (10kohm) – Circuit stability
       Jumper Wires & Connectors – For wiring and easy connections.

📎 8. Structural & Mechanical Parts
       Solar Panel Mounting Frame (Adjustable) – Holds the solar panel.
       3D Printed / Laser Cut Parts (Optional) – Custom enclosure for electronics.

🛠️ Tools Required
🔹 Soldering Iron & Solder Wire
🔹 Multimeter (For circuit testing)
🔹 Screwdriver Set & Drill Machine
🔹 Wire Stripper & Cutter
🔹 3D Printer (Optional for custom parts)


# 🚀 Real-Time GPS Tracker with SOS & Remote Audio Monitoring

An advanced IoT-enabled GPS tracking system developed using ESP32, GSM, and GNSS technologies for real-time location monitoring and emergency communication. This compact device is designed to provide live tracking, instant SOS alerts, and remote audio monitoring for enhanced safety and security applications.


## 📍 Key Features

* 🌍 Live GPS Tracking with periodic location updates
* 🚨 Emergency SOS Button with SMS alert and automatic calling
* 📞 Auto Call Answering for remote ambient audio monitoring
* 📊 Trip Analytics including speed, distance, and route tracking
* 🌐 IoT Dashboard Integration for real-time monitoring
* 🔧 User-Friendly Setup with minimal configuration requirements


## 🧰 Hardware Components

* Seeed Studio XIAO ESP32-C3
* SIM800L GSM Module
* GP-02 GNSS Module
* Rechargeable Battery
* Microphone Module
* SOS and Configuration Push Buttons
* Supporting Components (Resistors, Capacitors, PCB, etc.)


## ⚙️ System Working

1. The GNSS module continuously collects real-time geographic coordinates.
2. The ESP32 processes the incoming GPS data.
3. Using the SIM800L GSM module, the device transmits tracking information to the connected IoT platform.
4. Users can monitor the device location remotely through the cloud dashboard.
5. In emergency situations, pressing the SOS button:

   * Sends an alert SMS with the live location
   * Automatically places a call to predefined emergency contacts
6. Incoming calls can be auto-answered, enabling remote live audio monitoring through the onboard microphone.


## 🌐 Applications

* Personal safety systems
* Vehicle tracking
* Child and elderly monitoring
* Asset tracking
* Emergency response systems
* Remote surveillance solutions


## 💡 Future Enhancements

* Mobile app integration
* Geofencing alerts
* Battery optimization
* Real-time notifications
* Google Maps route visualization
* Multi-user monitoring support

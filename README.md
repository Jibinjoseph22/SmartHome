# Home Automation IoT App 🏠🔌
![](https://github.com/user-attachments/assets/dffd1315-beec-4e40-a807-2f1afa19a76f)


This **Flutter-Firebase-based mobile application** enables users to control their smart home devices remotely. The app integrates with **NodeMCU (ESP8266/ESP32)** via IP address configuration, allowing seamless home automation.

## 🚀 Key Features

✅ **Device Integration** – Users can add their **NodeMCU IP address** to connect with their smart home devices.  
✅ **Smart Controls** – Control home appliances such as:
   - **Door lock with fingerprint access**
   - **Gate lock**
   - **4 lights & 2 fans**
   - **Night Mode** – One-tap action to **lock doors and gates, and turn off all lights**  
✅ **Sensor Monitoring** – Real-time display of sensor values, including:
   - **Soil Moisture**
   - **Temperature**
   - **Humidity**
   - **Light Intensity**  
✅ **Data Visualization** – Graphs for tracking **historical sensor data**.  
✅ **Smart Farming Assistance** – Users can search for a **crop name** and get recommendations on the ideal **soil moisture, temperature, humidity, and light intensity** for that crop.  

## 🛠 Tech Stack

🚀 **Flutter** – Cross-platform mobile app development.  
☁ **Firebase** – Used for authentication, real-time database, and cloud storage.  
🌐 **NodeMCU (ESP8266/ESP32)** – Microcontroller for IoT device control.  
📊 **Graph Library** – Used for sensor data visualization.  

This app provides a **smart, efficient, and intuitive solution** for **home automation and IoT-based farming assistance**, making it a perfect companion for modern smart homes. 🏡⚡

## 📦 Installation Steps

1. **Clone the repository**
   ```sh
   git clone https://github.com/jibinjoseph22/SmartHome.git
   cd SmartHome
   ```

2. **Install dependencies**
   ```sh
   flutter pub get
   ```

3. **Set up Firebase**
   - Create a Firebase project on [Firebase Console](https://console.firebase.google.com/)
   - Enable **Authentication**, **Firestore Database**, and **Cloud Storage**
   - Download `google-services.json` (for Android) and place it inside `android/app/`

4. **Run the app**
   ```sh
   flutter run
   ```

## 📩 Contact

For any issues or suggestions, feel free to **raise an issue** or **contact me at**:  
📧 jibinjoseph2246@gmail.com.com   
📂 [LinkedIn](www.linkedin.com/in/jibinjoseph2)  

---
Made with ❤️ using Flutter, Firebase & IoT. 🚀

# ROV-Real-Time-Sensor-Processing-System-FreeRTOS-Based-
FreeRTOS-based multi-sensor real-time processing system with task scheduling and inter-task communication.
# ROV Sensor Data Processing System (FreeRTOS Based)

This project is a real-time embedded system designed using FreeRTOS for managing multiple sensor inputs in a coordinated and thread-safe manner.

The system simulates a Remotely Operated Vehicle (ROV) architecture where multiple sensors (Depth, Pressure, Temperature) operate concurrently and send data to a central processing unit.

## 🚀 Key Features

- Real-time multitasking using FreeRTOS
- Producer–Consumer architecture using Queue
- Thread-safe resource management using Mutex
- System synchronization using Counting Semaphore
- Modular sensor task design
- Non-blocking motor/control task for data processing

## 🧠 System Architecture

Sensor tasks act as **producers**, generating data periodically or once, while the Motor Control Task acts as a **consumer**, processing incoming data from a shared queue.

Synchronization ensures all sensors are initialized before the system starts processing data.

## ⚙️ Technologies Used

- C / C++
- FreeRTOS
- Embedded Systems (ESP32 / Arduino compatible)

## 📌 Use Case

This project demonstrates how real-time embedded systems handle concurrency, synchronization, and inter-task communication in robotics and IoT applications.

## 🔮 Future Improvements

- Real sensor integration (I2C / ADC modules)
- MQTT-based IoT data transmission
- PID-based motor control
- Data logging to external storage

- ## 👨‍💻 Author

Emre

# Vehicle_Accident_detection_project
This project is a real-time Accident Detection and Alert System built using Arduino, designed to enhance vehicle safety by monitoring key conditions such as seat belt usage, alcohol levels, and collision impacts. Upon detecting an accident, the system automatically sends an SMS with GPS coordinates to a predefined contact, facilitating faster emergency response.

# Components Used:
Arduino UNO
GSM Module (SIM800L or similar)
GPS Module (Neo-6M)
Alcohol Sensor (MQ-3)
Vibration Sensor
IR Sensor (for seat belt detection)
LCD Display (16x2)
Relay Module
Buzzer
Power Supply and Jump Wires

# Core Features:
Seat Belt Detection:
Uses an IR sensor to ensure the driver is wearing the seat belt.
If not worn, the vehicle won't start and a buzzer alert is triggered.

Alcohol Detection:
Detects the presence of alcohol using an MQ-3 sensor.
Prevents vehicle ignition if alcohol is detected.

Accident Detection
A vibration sensor identifies sudden impacts or accidents.
Automatically triggers the alert mechanism.

GPS Location Tracking
GPS module fetches real-time coordinates.
Sends location via SMS using a GSM module in the event of an accident.

SMS Alert System
Sends an SMS to an emergency contact with a message and GPS coordinates.

# How It Works
The system initializes and displays a welcome message.
It checks if the seat belt is worn via IR sensor.
If the seat belt is detected, it checks for alcohol.
If no alcohol is detected, it allows the vehicle to start.
While the vehicle is running, it continuously monitors for vibration.
If an accident is detected:
The system displays a warning on the LCD.
Sends an SMS with a predefined message and location to a stored mobile number.
Continuously updates GPS data on the serial monitor.
 

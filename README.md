# Prepaid Electricity Meter (Automation of Energy Meter Billing System)

## Project Objective
The objective of this project is to automate energy meter billing, reduce queues at billing counters, and ensure disconnection of power supply if the bill is unpaid. Additionally, it aims to detect unauthorized access or theft attempts for enhanced security.

## Components Used
- **Arduino Uno**: Microcontroller for controlling the entire system.
- **GSM Module (SIM800A)**: For enabling remote communication (if implemented).
- **Relay**: To control the power supply to the load.
- **Current Sensor (ACS)**: For measuring energy consumption.
- **Ultrasonic Sensor**: For detecting unauthorized access or tampering.
- **LCD (16x2)**: For displaying real-time updates such as balance and consumption data.
- **Load (Bulb)**: Simulating the energy consumption load.
- **Breadboard and Supporting Components**: For circuit connections.

## Features
1. **Automated Billing:**
   - Allows users to recharge a specific amount, converting it into energy units.
   - Automatically disconnects power when the balance is low or exhausted.

2. **Theft Detection:**
   - Ultrasonic sensor monitors the meter cover to detect tampering.
   - Alerts users about unauthorized access.

3. **Real-Time Monitoring:**
   - Displays remaining balance, consumed units, and current wattage on an LCD.
   - Updates the data dynamically based on usage.

4. **Energy Management:**
   - Tracks electricity usage and deducts units accordingly.
   - Notifies users to recharge when the balance is low.

## Questions (KPIs)
1. **Billing and Usage:**
   - How much balance remains after consumption?
   - What are the total units consumed?

2. **Theft Alerts:**
   - Are there any tampering attempts detected?

3. **Energy Consumption Insights:**
   - How many watts are being consumed?
   - How much energy is used over a specific period?

4. **Automation:**
   - Does the system automatically cut off power when the balance is exhausted?
   - Is the recharge process user-friendly and efficient?

## Video Demonstration
![Project Demonstration Video](https://github.com/Vedant-Jawalekar/Prepaid-Electricity-Meter/blob/main/VID-20250108-WA0013.mp4)

## Circuit Diagram

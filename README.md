LifePath — Smart Ambulance Traffic Management System

Overview

LifePath is a hardware-and-software-based traffic management system designed to reduce ambulance delays at traffic signals.

Problem

Ambulances may lose valuable time when they are delayed by traffic signals during emergencies. LifePath aims to provide advance warnings and help clear a path for approaching ambulances.

How It Works

- The ambulance's live location is sent to Firebase.
- A React dashboard monitors the ambulance's location.
- When the ambulance is more than 1 km away, the traffic signal works normally.
- Within 1 km, a blue warning light starts blinking.
- Within 500 m, the blue light glows continuously and the green light remains on to indicate that vehicles should clear the way.
- After the ambulance passes, the signal can return to normal operation.

Technologies Used

- React
- Python
- C++
- Firebase

Project Type

Hardware + Software + IoT + Smart Transportation

Project Status

Prototype under development.

Future Improvements

- Support for multiple ambulances
- Multiple connected traffic signals
- Improved GPS accuracy
- Emergency control-centre dashboard

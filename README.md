# Voice-Controlled-Wheel-chair with Environmental Mapping
# Introduction
This project aims to create a voice-controlled wheelchair that can also perform environmental mapping using an ultrasonic sensor and an RPLIDAR. The wheelchair can be controlled using voice commands, making it easier for individuals with mobility impairments to navigate. Additionally, the wheelchair is equipped with an ultrasonic sensor to avoid obstacles, and an RPLIDAR is used to create a map of the wheelchair's surroundings.

# Requirements
Before running the code, ensure that you have the following components:

# Raspberry Pi
Motor Driver (for controlling wheelchair movement)
Voice module (for voice recognition)
Ultrasonic Sensor (HC-SR04) and its required libraries (code in distance.py)
RPLIDAR and its required libraries (code in rp_lidar/ folder)
# Setup Instructions
Connect the motor driver to the Raspberry Pi to control the wheelchair movement. Refer to the motor driver's documentation for wiring details.

Connect the voice module to the Raspberry Pi to enable voice recognition. The voice.py script will handle voice commands.

Connect the ultrasonic sensor (HC-SR04) to the Raspberry Pi. Make sure to install the required libraries by running distance.py.

Connect the RPLIDAR to the Raspberry Pi using the provided libraries in the rp_lidar/ folder. The RPLIDAR will be used for environmental mapping.

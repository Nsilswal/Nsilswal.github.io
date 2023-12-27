---
title: "SmartGlasses"
excerpt: "Wearable SmartGlasses using RaspberryPi<br/><img src='/images/smartGlasses.png'>"
collection: portfolio
---

Demo Video: https://www.youtube.com/watch?v=yibkjnsFtRA&t=43s
Github: https://github.com/meganjfong/ECE495_SmartGlasses

# Smart Glasses Project Repository

This repository contains the code and documentation for a smart glasses project developed by Megan Fong and Nirvan Silswal. The smart glasses project incorporates various functionalities including timedate and weather display, translation capabilities, a music player, and Dropbox file upload functionality. This was created for a final project for the Duke University ECE495/CS390 course led by professor Tingjun Chen.

## Features

### Time and Date Display
- **Purpose:** Display live time and date information on the smart glasses.
- **Implementation:** Utilizes Python's datetime module to retrieve and display current time and date information on the OLED display.

### Weather Display
- **Purpose:** Provides real-time weather information based on the user's location.
- **Implementation:** Accesses OpenWeatherMap API to fetch weather data and displays it on the OLED screen.

### Translation Integration
- **Purpose:** Allows users to input text for translation and displays the translated text on the smart glasses.
- **Implementation:** Uses Google Translate module to prompt the user for text input, specify the target language, and output the translated text on the OLED display.

### Music Player
- **Purpose:** Enables users to play music wirelessly or through GPIO-connected speakers.
- **Implementation:** Incorporates functionality to play music using Python's pygame module and GPIO-connected speakers.

### Dropbox Upload
- **Purpose:** Allows users to upload files to Dropbox from the smart glasses.
- **Implementation:** Integrates with Dropbox API to facilitate the uploading of files to individual Dropbox storages.

## System Setup and Installation

To set up and run the smart glasses project on your Raspberry Pi or similar hardware, follow these steps:

1. **Hardware Requirements:**
   - Raspberry Pi 0w or compatible central processing unit
   - Transparent OLED display
   - Adafruit 500c or similar charging circuit and voltage regulator
   - Li-po battery or alternative power supply
   - Speakers (GPIO-connected or Bluetooth)
   
2. **Software Requirements:**
   - Raspbian OS or compatible operating system
   - Python libraries including datetime, requests, pygame, etc.
   - Access to OpenWeatherMap, Google Translate, and Dropbox APIs
   
3. **Installation Steps:**
   - Clone this repository to your Raspberry Pi or development environment.
   - Set up the hardware components as described in the hardware setup documentation ([accessible here](https://www.waveshare.com/wiki/1.51inch_Transparent_OLED)).
   - Install required Python libraries using pip or your preferred package manager.
   - Set up API keys for OpenWeatherMap, Google Translate, and Dropbox as per their respective documentation.
   - Run the Python scripts to activate the smart glasses functionalities.

## Usage

- **Time and Date Display:** Run the corresponding script to display live time and date information.
- **Weather Display:** Execute the weather display script to fetch and show real-time weather data.
- **Translation Integration:** Launch the translation script to input text for translation and view the translated output.
- **Music Player:** Utilize the music player script to play music either wirelessly or through connected speakers.
- **Dropbox Upload:** Run the Dropbox upload script to upload files to Dropbox from the smart glasses.

## Contributors

- Megan Fong ([GitHub Profile](https://github.com/meganjfong))
- Nirvan Silswal ([GitHub Profile](https://github.com/Nsilswal))


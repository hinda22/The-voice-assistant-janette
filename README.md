# The-voice-assistant-janette
 Intelligent Voice Assistant developed with Python and Arduino, featuring speech recognition, AI-powered responses, weather forecasting, web search, YouTube playback, and smart plant monitoring with automatic irrigation.
# The Voice Assistant Project

An intelligent voice assistant developed using Python and Arduino, capable of recognizing voice commands, answering questions using AI, performing web searches, monitoring plant humidity, and automating irrigation.

##  Overview

The Voice Assistant Project combines Artificial Intelligence, Voice Recognition, Home Automation, and Sensor Monitoring into a single interactive system.

The assistant can communicate with users through speech, perform online searches, provide weather information, play media, monitor environmental conditions, and automatically water plants when needed.

## Features

###  Voice Recognition

* Converts spoken commands into text.
* Supports French language recognition.
* Real-time voice interaction.

### Speech Synthesis

* Responds using natural voice output.
* Adjustable speech speed and voice settings.

###  AI-Powered Responses

* Answers general questions using Google Generative AI.
* Provides intelligent conversational interactions.

###  Online Search

* Google search integration.
* Information retrieval from the web.
* Automatic opening of search results.

###  YouTube Integration

* Search for videos.
* Play requested songs or media content.

###  Weather Information

* Retrieves weather forecasts.
* Provides weather-related responses through voice.

###  Time Service

* Announces the current time upon request.

###  Social Media Access

* Opens Facebook directly through voice commands.

###  Smart Plant Monitoring

* Reads humidity sensor values.
* Monitors soil moisture levels.
* Displays plant status.

###  Automatic Irrigation

* Activates a water pump when humidity drops below a predefined threshold.
* Helps maintain healthy plant conditions automatically.

---

##  System Architecture

The project consists of two interconnected subsystems:

### Software Side (Python)

* Voice Recognition
* Speech Synthesis
* AI Processing
* Web Search
* GUI Management
* WiFi Communication

### Hardware Side (Arduino)

* Humidity Sensor
* Water Pump
* Sensor Data Acquisition
* Irrigation Control

Communication between Python and Arduino is performed through WiFi using socket programming.

---

## Technologies Used

### Programming Languages

* Python
* Arduino C/C++

### Python Libraries

```bash
speech_recognition
pyttsx3
customtkinter
requests
beautifulsoup4
datetime
google-generativeai
webbrowser
googlesearch-python
youtube-search
socket
```

### Hardware Components

* Arduino Board
* Soil Humidity Sensor
* Water Pump
* WiFi Module
* Computer with Microphone and Speakers

---

##  Project Structure

```text
The-Voice-Assistant-Project/
│
├── main.py
├── gui.py
├── speech_recognition_module.py
├── text_to_speech.py
├── ai_assistant.py
├── weather.py
├── google_search.py
├── youtube_player.py
├── plant_monitor.py
├── wifi_communication.py
│
├── Arduino/
│   └── plant_monitoring.ino
│
├── Images/
│   ├── interface.png
│   ├── architecture.png
│   └── testing.png
│
└── README.md
```

---

## How It Works

1. User speaks a command.
2. Speech Recognition converts audio into text.
3. Command is analyzed.
4. Appropriate module executes the requested action:

   * Search Google
   * Ask AI
   * Play YouTube content
   * Tell time
   * Retrieve weather information
   * Open Facebook
   * Monitor plant humidity
5. Response is generated.
6. Speech Synthesis converts the response into audio.
7. If plant monitoring is requested, humidity data is retrieved from Arduino and irrigation is triggered if necessary.

---

##  Demonstration

The system includes:

* Interactive CustomTkinter graphical interface.
* Real-time voice interaction.
* Humidity monitoring dashboard.
* Automated pump control.

---

##  Testing Results

### Voice Commands

* Reliable recognition of common commands.
* Stable voice interaction in normal environments.

### Plant Monitoring

* Accurate humidity measurements.
* Successful automatic pump activation when required.






 Hind Saada


Faculty of Sciences of Bizerte (FSB)
University of Carthage

Academic Year: 2024–2025






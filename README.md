# Eye_Disease_Detection


TITLE : IOT-ENABLED SMART VISION ANALYZER AND RETINAL SCREENING SYSTEM

PROJECT DESCRIPTION:

This project proposes an IoT-enabled Smart Vision Analyzer designed to detect eye diseases at an early stage using Artificial Intelligence and IoT. The system provides real-time retinal disease detection and displays the result through both web dashboard and IoT hardware.

The system helps to overcome limitations of traditional methods which are either software-based or hardware-based, reducing diagnosis time and preventing vision loss. It is suitable for both rural and urban healthcare.

When the user uploads a retinal image, the system:

1. Performs image preprocessing and removes noise
2. Uses CNN-based AI model to detect disease
3. Displays result with confidence score
4. Sends output to LCD display via ESP8266
5. Provides medical recommendations
6. Sends notification to patient via cloud

The system integrates Python, OpenCV, Flask, Deep Learning (CNN), and IoT communication (UDP) to provide fast and reliable healthcare support.


HARDWARE REQUIREMENTS

Processor       : Intel Processor 2.6 GHz or above
RAM	        : 8 GB
Microcontroller	: ESP8266
Display Unit	: 16×2 LCD
Power Supply	: Regulated DC Power Supply

SOFTWARE REQUIREMENTS

Server Side	: Python 3.x
Client Side	: HTML, CSS, Bootstrap
CLI	        : Anaconda Prompt
Image Processing: OpenCV, NumPy
Back End	: Flask
Database	: MySQL
OS	        : Windows 11

CONNECTION STEPS:

STEP 1: Power Supply Connection

--> Connect power supply adapter to the hardware setup
--> Ensure proper voltage distribution to ESP8266 and LCD

STEP 2: Microcontroller Setup

--> ESP8266 acts as the main controller
--> Controls communication and data transfer

STEP 3: LCD Display Connection

--> LCD connected to ESP8266
--> Displays disease result and confidence score

STEP 4: UDP Communication Setup

--> Establish UDP connection between software and hardware
--> Ensures real-time data transmission

STEP 5: WiFi Setup

--> Turn ON mobile hotspot
--> Set:
WiFi Name  : projectiot
Password   : projectiot1

--> Connect both PC and ESP8266 to this WiFi

STEP 6: Hardware Activation

--> Plug in power supply
--> Blue light indicates hardware is active and connected

STEP 7: Connect System to PC

--> Ensure PC is connected to same WiFi network
--> Hardware and software are now ready

HOW TO RUN:

STEP 1: Install Required Software

--> Install Python 3.x
--> Install Anaconda Prompt

STEP 2: Activate Environment

--> Open Anaconda Prompt

```bash
conda activate py310
```

STEP 3: Navigate to Project Folder

--> Copy project folder path

```bash
cd your_project_path
```

STEP 4: Run the Application

```bash
python app.py
```

STEP 5: Open Web Dashboard

--> Copy the localhost link from terminal
--> Open in browser (e.g., http://127.0.0.1:5000/)

STEP 6: User Registration

--> New users must register using their details

STEP 7: User Login

--> Login with username and password (secure authentication)

STEP 8: Upload Image

--> Upload retinal image from dataset

STEP 9: Analyze Image

--> Click "Analyze"
--> AI model detects disease and gives output

STEP 10: View Results

--> Results displayed on:

* Web dashboard
* LCD display (IoT hardware)

STEP 11: Notifications

-->Patient receives result via cloud notification
--> Doctor can view instant result on LCD display



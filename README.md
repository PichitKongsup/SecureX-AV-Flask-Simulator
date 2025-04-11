# SecureX-AV-Flask-Simulator
The Antivirus Simulator project, developed in Python using the Flask framework, is an interactive application designed to simulate the operation of antivirus software in real-time. The application allows users to perform various types of scans, including quick and full scans, detect threats, and interact with real-time protection.

# Technologies used in the project:
# Python:
The main programming language used for the application's logic and the simulation of the scanning process and threat detection. Python enabled the development of a multi-threaded application (using the threading module) to run simulations concurrently with user interactions.

# Flask:
A web framework used to build the backend of the application, handle HTTP requests, interact with the frontend, and manage the application state. Flask allowed for the creation of a lightweight, functional web application that can be easily extended with new features.

# HTML5 & CSS3:
Web standards used to build the structure and design of the application. HTML5 provided the markup for the user interface, while CSS3 ensured an aesthetically pleasing and responsive design, making the app usable on various devices.

# JavaScript:
JavaScript was used for dynamic user interaction, such as updating the progress bar, playing notification sounds, and updating the interface in real-time, along with asynchronous requests to the server (AJAX) to ensure smooth user experience.

# Multithreading (threading module):
Used to perform the scanning process and user interactions concurrently, allowing users to stop the scan or modify settings while the scan is ongoing.

# Simulated Files:
SIMULATED_FILES is a list of files used to simulate the scanning process. The application randomly selects files to scan and introduces random threats to mimic the real behavior of antivirus software.

# Key Features of the Application:
File Scanning: Users can initiate either a quick or a full scan of the system. The process simulates searching various locations in the system and detecting threats such as viruses or malware.

# Threat Detection: 
During the scan, the application randomly detects threats in selected files. If threats are found, users receive an alert, and the "Fix" button becomes available to "remove" the detected threats.

# Real-Time Protection (RTP): 
Users can toggle real-time protection, affecting how the application responds to detected threats.

# VPN: 
The app allows users to start or stop a Virtual Private Network (VPN), simulating the protection of user privacy when browsing the web.

# User Interface: 
The application features a clear and intuitive interface displaying information about the scan's progress, current file being scanned, and the status of features like VPN and RTP. Additionally, users receive sound notifications when a scan starts and completes.

# Multithreading and Asynchronous Processing: 
The scanning process runs in parallel with user interactions, thanks to multithreading. Asynchronous requests (AJAX) ensure real-time updates of the application state without needing to reload the page.

# Project Summary:
The Antivirus Simulator project combines education with practical application in the field of cybersecurity. Using technologies like Python, Flask, HTML5, CSS3, and JavaScript, it offers an interactive and feature-rich application for simulating antivirus software. This application allows users to see how antivirus software operates in real-time, making it an invaluable educational tool for learning about IT security.

Instructions for using the program:

# STEP 1: Install python from the official site: https://www.python.org/
# STEP 2: Install Visual Studio Code the offiicial site: https://code.visualstudio.com/
# STEP 3: Run the code.
# STEP 4: Enter the WEB application via the site's IP

# the application is open-source and available exclusively for developers who are interested in contributing to its growth, improvement, or adaptation to specific use cases.

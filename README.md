<h1>Web-Based Motor Control & Data Analysis</h1>

<h2>Description</h2>
A web application designed to control and test motors used for measuring airflow in an EOS 3D printer. The platform also enables real-time data visualization, analysis, and download functionality for test results.

Features:
Motor Control & Testing: Interface for controlling and testing airflow measurement probes.

Real-Time Graph Generation: Displays sensor data dynamically.

Data Persistence & State Indicators: Ensures accurate tracking of test conditions.

Data Analysis & Export: Users can visualize and download test results for further study.

UI/UX Enhancements: Redesigned interface for improved user experience.

Technologies Used:
Frontend: HTML, CSS, JavaScript

Backend: Python (Server Response Handling)

Data Handling: Real-time graph generation, state indicators
<br />


<h2>Languages and Utilities Used</h2>

<b>Technologies Used:

Frontend: HTML, CSS, JavaScript

Backend: Python (Server Response Handling)

Data Handling: Real-time graph generation, state indicators</b>

<h2>Environments Used </h2>
<b>Web Browser (Frontend Testing), Local Server (Python Backend)</b> 

<h2>Program walk-through:</h2>

<p align="center">
Walkthrough of Functionality
1. Frontend (main.html & data_collection.html)
User Interface:

main.html serves as the main UI for controlling the motor and starting the data collection.

data_collection.html is responsible for displaying real-time airflow measurement data in graphical form.

Real-Time Graph Generation:

JavaScript is used to fetch live sensor data and plot it dynamically using a graphing library (likely Chart.js or similar).

State Indicators & Data Persistence:

UI elements show the status of the airflow measurements, ensuring that users can track the state of the test.

Main Page: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Graph and Data Analytics: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

2. Backend (app.py)
Server Role:

Written in Python using Flask, the backend manages data collection from the airflow sensors and serves it to the frontend.

It provides RESTful endpoints to send sensor readings to the JavaScript running in the browser.

Data Analysis & Export:

The Python backend processes and stores the data.

It allows users to download collected data in a structured format (CSV or JSON) for further study.
</p>

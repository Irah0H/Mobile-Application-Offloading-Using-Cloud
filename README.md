
# Mobile Application Offloading Using Cloud

## Description
This project demonstrates offloading resource-intensive computations from mobile devices to a cloud server, optimizing performance and extending battery life.

## Features
- Real-time computation offloading to a cloud server.
- Improved performance and reduced energy consumption on mobile devices.
- Secure data transmission between client and server.

## Setup Instructions

### Cloud Server
1. Navigate to the `cloud_server` directory:
cd cloud_server
## Install required dependencies:
pip install -r requirements.txt
## Run the server:
python server.py


## Mobile Client
Navigate to the mobile_client directory.
Set up the mobile app on your emulator or device (details in the documentation).
Start the app and connect to the server.
### Usage
Start the cloud server using server.py.
Launch the mobile client app.
Select the operation you want to offload, and the server will handle the computation.



### Technologies Used
Python: For server and prototype client.
Flask/Django: Backend server framework (if applicable).
Android/iOS: Mobile client (or simulation using Python GUI).
RESTful API: Communication between client and server.
Cloud Platform: AWS, Google Cloud, or local simulation.

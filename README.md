 # unlockr-access-control-with-arduino-uno-and-mobile-integration
**Project Title: UNLOCKR - Access Control with Arduino Uno and Mobile Integration** 

This project is a automated gate system designed to help persons with disabilities (PWDs) open and close their gates easily. It uses an Arduino Uno to control the gate and a Flutter mobile app to operate it. Instead of struggling with heavy gates, users can simply press a button in the app to open or close the gate remotely. The system works by connecting the Arduino to a hinge that moves the gate. The app communicates with the Arduino through Bluetooth, making it convenient to use. 

**Technologies Used:**
1. Figma: A collaborative design tool to create UI/UX designs for your mobile app and prototypes for the user interface.
2. Flutter: A UI toolkit for building natively compiled applications for mobile, web, and desktop from a single codebase, perfect for creating a custom mobile interface for your Arduino project.
3. Arduino IDE: For programming the Arduino board.
4. Firebase: For cloud storage and real-time database interactions, useful for more complex functionalities.

 **Features:**
1. Accessible for PWDs - The system will be specifically designed for persons who are having difficulty with their disabilities on a daily basis. This will aid them to open and close doors easily.
2. Enhanced Security Convenience - It eliminates the need for physical keys and becomes more convenient
3. Simple Design and Integration - The system will be easy to set up, making gate operation hassle-free.
4. Data Logging - The system will record and track the past gates' activity and usage.

**Installation Instructions:**
1. Install Flutter SDK - Follow the official Flutter installation guide to install Flutter on your machine.
2. Install Git - Ensure you have Git installed for cloning the repository.
3. Set Up an Editor - Use an IDE like Visual Studio Code or Android Studio with Flutter and Dart plugins installed.


Step 1: Clone the Repository
1. Open your terminal (Command Prompt, PowerShell, or Terminal).
2. Navigate to the directory where you want to clone the project.
3. Run the following command to clone the GitHub or GitLab repository:
   
   git clone https://github.com/NicoleSurigao/unlockr-access-control-with-arduino-uno-and-mobile-integration.git

Step 2: Navigate to the Project Directory

Change into the project directory: cd unlockr-access-control-with-arduino-uno-and-mobile-integration 

Step 3: Install Dependencies

Run the following command to install the necessary dependencies:  flutter pub get

Step 4: Connect Your Device or Start an Emulator
1. Connect a Physical Device
   - If you have a physical device, enable developer mode and USB debugging.
   - Connect your device to your computer via USB.
2. Start an Emulator:
   - If you prefer to use an emulator, start it from your IDE or by running: 
                  flutter emulators --launch <emulator_id>

Step 5: Run the Application
Now, you can run the application using the following command: flutter run


Step 6: Troubleshooting
If you encounter any issues, ensure that:
- All Flutter dependencies are installed correctly.
- The device or emulator is recognized by Flutter. You can check this using: flutter devices
- Make sure to check the console for any error messages during the run process.


**Instructions for setting up IoT devices and cloud services.**

Step 1: Gather Hardware Components
Collect the necessary components:
Arduino board (e.g., Arduino Uno)
Motorized gate mechanism
Bluetooth module (e.g., HC-05)
Sensors (e.g., water level sensor)
Power supply
Jumper wires and breadboard (if needed)

Step 2: Hardware Setup
Wiring:
Connect the motor driver to the Arduino.
Attach the Bluetooth module to the Arduino's TX/RX pins.
Connect the water level sensor to the appropriate analog pin on the Arduino.
Ensure all power supply connections are secure.

Step 3: Software Setup
Install Arduino IDE:
Download and install the Arduino IDE.
Connect Arduino:
Connect the Arduino board to your computer via USB.
Open IDE:
Launch the Arduino IDE and select the correct board and port.
Upload Code:
Write or download the Arduino sketch that includes:
Bluetooth communication setup
Motor control logic based on Bluetooth commands
Data logging functionality to record gate activity
Upload this code to the Arduino.

Step 4: Cloud Integration
Choose a Cloud Platform:
Select a cloud service (e.g., AWS IoT, Google Cloud IoT, or Azure IoT).
Create an account and set up a project.
Device Registration:
Register your Arduino device within the chosen cloud service.
Obtain necessary credentials (device ID, secret key).
Data Streaming:
Implement MQTT or HTTP protocol in your Arduino code to send data to the cloud.
Utilize the cloud service's SDK or API for communication.

Step 5: Mobile Application Development
Select Development Framework:
Choose a framework like Flutter or React Native for cross-platform compatibility.
Implement App Functionality:
Develop features for remote gate control (open/close).
Set up notifications for gate status changes.
Integrate a data logging display for users to track activity.

Step 6: Testing and Validation
Conduct thorough testing of the entire system:
Ensure the gate can be opened and closed via the app.
Verify Bluetooth communication between the app and Arduino.
Check that data is accurately logged and displayed in the cloud.

Step 7: Deployment
Install the system at the desired location.
Ensure all components are securely mounted and easily accessible.

Step 8: User Training
Provide instructions to users on how to use the mobile application.
Ensure users understand how to control the gate and view logs.

Step 9: Maintenance and Support
Regularly check the system for updates and ensure the cloud service operates smoothly.
Provide ongoing support for troubleshooting any issues that may arise.

# BLE-Scanner
A simple Android application that scans for nearby Bluetooth Low Energy (BLE) devices and displays the scanned devices in a list.
# Usage
Launch the application on a physical Android device that supports BLE.
Grant Bluetooth permissions if prompted.
Press the "Scan" button to start scanning for nearby BLE devices.
Scanned devices will appear in the list view with their name and MAC address.
To stop scanning, press the "Stop" button.
Interact with the scanned devices as required.
# Dependencies
Minimum Android SDK version: 21
AndroidX libraries for UI components and Bluetooth API

# Development Steps
Set up the project structure and UI layout.
Request necessary Bluetooth permissions in the AndroidManifest.xml file.
Initialize BluetoothAdapter and check for BLE support.
Implement the scanning logic using BluetoothLeScanner.
Create a ScanCallback to handle scan results and update the UI.
Stop scanning when required.
Build and run the application on a physical Android device.

# Contributions
Contributions are welcome! If you would like to contribute to this project, please follow the standard Git workflow:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive messages.
Push your branch to your forked repository.
Open a pull request with a detailed explanation of your changes.

# License 
This project is licensed under the MIT License. See the LICENSE file for more details.

# BLE-Scanner
A simple Android application that scans for nearby Bluetooth Low Energy (BLE) devices and displays the scanned devices in a list.


<img  src="https://github.com/yesiamrajeev/BLE-Scanner/assets/125568812/c9d01894-15e4-4b34-8510-cb4c2abef363" width="250" height="500">

# Usage
Launch the application on a physical Android device that supports BLE.
Grant Bluetooth permissions if prompted.
Press the "Scan" button to start scanning for nearby BLE devices.
Scanned devices will appear in the list view with their name and MAC address.
To stop scanning, press the "Stop" button.
Interact with the scanned devices as required.
# Dependencies
Minimum Android SDK version: 33
AndroidX libraries for UI components and Bluetooth API

## Features

- Scan for nearby BLE devices.
- Display discovered devices' names and addresses in a list.
- Handle runtime permissions for Bluetooth and location access.
- Request Bluetooth activation if it's not enabled.
- Basic error handling for different scenarios.
## Libraries Used

- [Apache Commons IO](https://commons.apache.org/proper/commons-io/): Used for IO operations.
- [AndroidX AppCompat](https://developer.android.com/jetpack/androidx/releases/appcompat): Support library for material design features.
- [Apache POI](https://poi.apache.org/): Used for reading Excel files.
- [Android BLE API](https://developer.android.com/guide/topics/connectivity/bluetooth-le): Android's built-in Bluetooth Low Energy API.

## Future Improvements

- Enhance UI/UX design.
- Handle more edge cases for BLE and permissions.
- Store and retrieve scanned devices using a more robust data storage method.
- Provide more detailed device information.
- Add filtering options for discovered devices.

# Contributions
Contributions are welcome! If you would like to contribute to this project, please follow the standard Git workflow:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them with descriptive messages.
Push your branch to your forked repository.
Open a pull request with a detailed explanation of your changes.

# License 
This project is licensed under the MIT License. See the LICENSE file for more details.

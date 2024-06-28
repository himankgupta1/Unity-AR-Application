# Unity AR Application

A demo Augmented Reality (AR) application developed using Unity, intended to allow users to view a certain city as it appeared in ancient times. This initial version contains a simple 3D box model to demonstrate basic AR functionality.

## Features
- Basic AR environment setup
- Simple 3D box model placed in the AR scene
- Demonstrates potential for viewing ancient cities in AR

## Requirements
- Unity 2020.3 or later
- AR Foundation package
- ARCore XR Plugin (for Android) or ARKit XR Plugin (for iOS)

## Getting Started
### Prerequisites
1. Install Unity Hub: Download and install Unity Hub.
2. Install Unity: Through Unity Hub, install the Unity Editor (version 2020.3 or later).
3. Setup AR Foundation: Open your project in Unity, go to Window -> Package Manager, and install the AR Foundation package along with ARCore XR Plugin (for Android) or ARKit XR Plugin (for iOS).

### Project Setup
1. **Clone the repository**:
```bash
git clone https://github.com/yourusername/Unity-AR-App.git
```

2. Open the project: Open Unity Hub, click on Add, and select the cloned project folder.

3. Build settings:
- Go to File -> Build Settings.
- Select Android or iOS as your platform.
- Click on Switch Platform.

4. Player settings:

- In the Build Settings window, click on Player Settings.
- Under Other Settings, set the Package Name (for Android) or Bundle Identifier (for iOS).
- Enable ARCore or ARKit in the XR Settings section based on your target platform.

## Running the App
1. Connect your device:
- For Android, enable Developer Options and USB Debugging.
- For iOS, connect your device via USB and ensure it is registered in your Apple Developer account.

2. Build and Run:
- Go to File -> Build and Run.
- Unity will build the project and deploy it to your connected device.

## Usage
- Launch the app on your device.
- Grant necessary permissions for camera and AR functionality.
- Move your device around to detect surfaces and view the AR box.

## Deployment
- The app has been successfully deployed on Android.
- Attached are photos and videos showcasing the app in action.

## Contributing
Feel free to fork this repository and make improvements. Pull requests are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For questions, issues, or suggestions, please contact himankguptaa@gmail.com.

## Demonstration
https://github.com/himankgupta1/Unity-AR-Application/assets/142075465/c485498b-9360-4230-80c9-90a47c435847

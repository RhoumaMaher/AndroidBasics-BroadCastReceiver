# Broadcast Receivers Example App

This repository contains the source code for an Android app demonstrating the use of broadcast receivers. The app listens for changes in the airplane mode setting and logs whether it is enabled or disabled.

## Features

* **Dynamic Broadcast Receiver:** The app dynamically registers and unregisters the broadcast receiver at runtime.

* **Airplane Mode Detection:** Logs whether airplane mode is turned on or off.

* **Minimal Codebase:** Focuses solely on the essentials to help you understand broadcast receivers in Android.

## Code Overview

### Key Components

1. **AirPlaneModeReceiver:** A class that extends BroadcastReceiver to handle the broadcast for airplane mode changes.

2. **MainActivity:** The main activity where the receiver is registered and unregistered dynamically.

## Article Reference

For a detailed explanation of the code and concepts, check out the accompanying Medium article:

[Understanding Broadcast Receivers in Android with a Practical Example](https://medium.com/@maheraizen1/understanding-broadcast-receivers-in-android-with-a-practical-example-977a773970d8)

The article walks you through the implementation step by step and highlights best practices for working with broadcast receivers.

## How to Run

1. **Clone this repository.**

2. **Open the project in Android Studio.**

3. **Build and run the app on an emulator or physical device.**

4. **Enable and disable airplane mode on the device to see the logs in Logcat.**

## License

This project is licensed under the MIT License. Feel free to use and modify the code for your own projects.

Happy coding! If you have any questions or suggestions, feel free to reach out.

* **Medium:** [My Medium Profile](https://medium.com/@maheraizen1)

* **LinkedIn:** [My LinkedIn Profile](https://www.linkedin.com/in/maher-rhouma-581919199/)

Let’s connect and discuss all things Android!

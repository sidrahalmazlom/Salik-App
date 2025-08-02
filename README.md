# Salik - Road Safety Reporting App

**Salik** is a road safety reporting app that helps users in the **Aseer region** and beyond to report hazards, road closures, and weather conditions on the roads. This app is designed to enhance road safety by allowing users to report real-time issues such as accidents, road closures, flooding, or other hazards. It provides drivers with crucial safety tips and allows them to submit reports with photos for authorities to address.

---

## Features

- **Voice Command Integration**: Report issues using voice commands while driving.
- **Real-time Hazard Reporting**: Report hazards like accidents, road closures, and more.
- **Photo Submission**: Take and submit photos of the reported hazards or closures.
- **Weather Conditions Reporting**: Report weather conditions like fog, rain, and wind with instructions for handling each.
- **Easy-to-Tap Buttons**: Big, user-friendly buttons to ensure easy interaction while driving.
- **Safety Instructions**: Get real-time safety instructions based on the reported issue (e.g., how to handle fog, accidents, or road closures).
- **Location-Based Alerts**: Receive notifications when approaching a reported hazard or road closure.

---

## Technologies Used

- **Flutter**: The app is built using **Flutter**, a cross-platform framework, to create natively compiled applications for mobile from a single codebase.
- **Google Maps API**: Used for displaying maps and marking reported hazards or road closures.
- **Speech-to-Text**: To enable voice commands for reporting hazards and conditions.
- **Local Notifications**: For real-time alerts on road conditions or nearby hazards.
- **Geofencing**: To send notifications based on the user’s location.

---

## App Screens

1. **Welcome Screen**:
   - Displays options for **Log In** and **Sign Up**.

2. **Sign In Screen**:
   - Allows users to sign in with their username and password.

3. **OTP Verification**:
   - Verifies users through OTP sent to their phone number.

4. **Menu Screen**:
   - Easy access to **Drive Save**, **Hike Save**, and **Report**.
   - Includes a **bottom navigation bar** and **floating action button** for easy access.

5. **Hazard Reporting Screen**:
   - Users can report various types of hazards such as **Car Accident**, **Big Hole**, and **Flooding**.
   - Allows users to upload photos of the hazards.

6. **Road Closure Reporting Screen**:
   - Users can report road closures like **Left Lane Closed**, **Road Closed**, or **Detour**.
   - Also includes a **photo submission** feature.

7. **Weather Conditions Reporting Screen**:
   - Allows users to report conditions like **Rain**, **Fog**, and **Wind**.
   - Provides safety tips for each condition.

8. **Submit a Photo Screen**:
   - Users can choose multiple photos before submitting them as part of their report.

9. **Thank You Screen**:
   - Displays a confirmation message after the report is submitted successfully.

---

## Installation

### Prerequisites

1. **Flutter**: Make sure Flutter is installed on your system. Follow the installation instructions on the official [Flutter website](https://flutter.dev/docs/get-started/install).
2. **Android Studio or Visual Studio Code**: You can use either **Android Studio** or **Visual Studio Code** for development.

### Steps to Install

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/salik.git
    cd salik
    ```

2. Install dependencies using Flutter:

    ```bash
    flutter pub get
    ```

3. Connect your device or start an emulator.

4. Run the app:

    ```bash
    flutter run
    ```

---

## App Screenshots

Below are the screenshots from the **Salik** app:

![Menu Screen](screenshots/menu_screen.png)
*Menu Screen*

![Hazards Reporting](screenshots/hazards_reporting.png)
*Hazard Reporting Screen*

![Weather Conditions Reporting](screenshots/weather_conditions.png)
*Weather Conditions Reporting Screen*

---

## Contributions

If you want to contribute to the **Salik** project, feel free to open an issue or create a pull request. You can suggest new features, report bugs, or improve existing code.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

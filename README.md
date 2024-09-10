# Simple Android AlertDialog Example

This is a simple Android application demonstrating how to use an **AlertDialog** in an Android app. The app shows how to present a dialog to confirm an action (e.g., saving data) and handle the user’s response accordingly. Additionally, the app displays a **Toast** message upon launch and after interacting with the dialog.

## Features
- Display an **AlertDialog** to confirm actions (Save).
- Use **Toast** messages to show feedback to the user.
- Immersive UI with **EdgeToEdge** and **WindowInsetsCompat** for system bars handling.

## Technologies Used
- **Android Studio**
- **Java** 
- **AlertDialog**
- **Toast**
- **EdgeToEdge** and **WindowInsetsCompat** for immersive UI.

## Code Overview

### Main Components
1. **MainActivity**:  
   - Displays a **Toast** message when the app is launched.
   - Uses **AlertDialog.Builder** to create and show an alert dialog for confirming the save action.
   - The dialog provides two options:
     - **Yes**: Displays a "Saved" **Toast** message.
     - **No**: Displays a "Not Saved" **Toast** message.
     
2. **EdgeToEdge** and **WindowInsetsCompat** are used to adjust padding for system bars to improve the app’s visual experience.

### Methods
- **save(View view)**: This method triggers the **AlertDialog**. When the user presses the "Yes" button, a "Saved" **Toast** message is displayed. If the user presses "No", a "Not Saved" message is shown.

## Getting Started

### Prerequisites
To run this project, you need:
- Android Studio installed on your computer.
- Basic knowledge of Kotlin/Java and Android development.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/blueyes0101/AlertDialogAndroid
    ```

2. Open the project in Android Studio.

3. Build and run the project on an emulator or physical device.

## Usage

1. When the app is launched, a **Toast** message ("Toast Message") will appear.
2. To test the **AlertDialog**, press the **Save** button in the app:
   - If you select "Yes", a **Toast** message saying "Saved" will appear.
   - If you select "No", a **Toast** message saying "Not Saved" will appear.

## Contributing
Feel free to contribute by opening issues or submitting pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

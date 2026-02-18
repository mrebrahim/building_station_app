# Building Station Mobile App

This project is a Flutter application that wraps the [Building Station Mobile Hub](https://building-station-mobile-hub.lovable.app/) website in a WebView.

## Prerequisites

Since you are running on Windows, you need to install the **Flutter SDK** to run and build this application.

1.  **Install Flutter**: Follow the guide here: [https://docs.flutter.dev/get-started/install/windows](https://docs.flutter.dev/get-started/install/windows)
2.  **Enable Web/Android Support**: Run `flutter config --enable-web` or set up an Android Emulator (via Android Studio).

## How to Run

1.  Open this folder in a terminal (Command Prompt or PowerShell).
2.  Get dependencies:
    ```bash
    flutter pub get
    ```
3.  Run the app (ensure you have a connected device or emulator):
    ```bash
    flutter run
    ```

## Building for iOS

Building a native iOS app (`.ipa` file) requires macOS and Xcode. Since you are on Windows:

1.  **Develop & Test on Android/Windows**: Ensure the app works as expected using the steps above.
2.  **Build for iOS**:
    *   **Option A**: Move this project to a Mac computer and run `flutter build ios`.
    *   **Option B**: Use a cloud build service like **Codemagic**, **Bitrise**, or **GitHub Actions**. You can push this code to a GitHub repository and connect it to one of these services to generate the `.ipa` file without buying a Mac.

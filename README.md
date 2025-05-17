# Android-Control-Application
Setup Prerequisites Tools Required:
Visual Studio (for C#/.NET development)

Android SDK Platform Tools (ADB executable: adb.exe, AdbWinApi.dll, AdbWinUsbApi.dll)

Android Device:

Enable USB Debugging (Settings > Developer Options).

Use a compatible data cable.

Create a C# Windows Forms Project Open Visual Studio and create a Windows Forms App (.NET Framework).
Design the GUI with:

Buttons: Connect Device, Extract SMS, Extract Calls, Generate Report.

DataGridView/ListView to display results.

Status bar for connection/error messages.

Integrate ADB into the Project Include ADB Files:
Copy adb.exe, AdbWinApi.dll, and AdbWinUsbApi.dll into your project directory.

In Visual Studio, add these files to your project and set their properties to Copy to Output Directory: Copy always.

4.. Handle Permissions and Errors Device Authorization: Ensure the user grants USB debugging access on the device.

Error Handling: Wrap ADB commands in try-catch blocks and display errors in the UI.

5.Test the Application Connect the Android device via USB.

Run the app and click Connect.

Extract data (SMS, calls, installed apps).

Generate and verify the report.

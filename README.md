# Using OpenGL DLL with Minecraft and TLauncher

This guide provides instructions on how to use the OpenGL DLL file with Minecraft and TLauncher to improve performance or enable specific features.

## Installation Instructions:

1. **Extract the OpenGL DLL file:**
   - Extract the contents of "OpenglDll.zip" to a location on your computer.

2. **Copy the DLL file to specified paths:**
   - Navigate to the following directories:
     - `C:\Users\YOUR_USER_NAME\AppData\Roaming\.minecraft\runtime\jre-legacy\windows\jre-legacy\bin`
     - `C:\Users\YOUR_USER_NAME\AppData\Roaming\.minecraft\runtime\java-runtime-alpha\windows\java-runtime-alpha\bin`
     - `C:\Users\YOUR_USER_NAME\AppData\Roaming\.tlauncher\jvms\jre1.8.0_281\bin`
     - `C:\Program Files\Java\jre1.8.0_51\bin`
   - Copy the OpenGL DLL file into each of these directories.

3. **Configure TLauncher:**
   - Open TLauncher and go to the settings.
   - Navigate to the Java Settings or JVM Settings section.
   - Add the path to the directory where you copied the DLL file (`C:\Users\YOUR_USER_NAME\AppData\Roaming\.tlauncher\jvms\jre1.8.0_281\bin`) to the Java executable path or JVM path configuration in TLauncher.

4. **Launch Minecraft via TLauncher:**
   - Start Minecraft using TLauncher to utilize the OpenGL DLL file and benefit from improved performance or features.

## Additional Notes:
- Ensure you have appropriate permissions to copy files to the specified directories.
- Be cautious when modifying system files and directories.
- If encountering issues, consult TLauncher's documentation or seek assistance from the Minecraft/TLauncher community.


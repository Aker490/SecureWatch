**This program has the following important features:**

1. **Folder detection**: The program checks for the presence of a folder named "I Am Ktrr" on the user's desktop. If this folder is created, it is considered a user authentication and the computer can be accessed normally.
2. **Timeout feature**: The program has a timeout set. If the folder is not found within the specified time, the program will automatically shut down. (This feature can be enabled by uncommenting the related code.)
3. **Automatic installation of required libraries**: The program will automatically check and install the missing required libraries if they are not present on the system.
4. **Moving the program to the default folder**: The program will copy itself to the default folder to ensure that the program will run automatically every time the computer starts.
5. **Background operation**: The program runs in the background using threads, allowing it to simultaneously check for folders and timeouts without interrupting the system.

This program is designed to secure your computer by creating a system of authentication based on the specified folders. If the authentication folder is not detected within the specified time, the system will shut down to prevent unauthorized access.

Note: The EXE version may trigger an antivirus warning due to its behavior, but the source code is provided here for transparency.

Note: If this project gets 10 stars, I will share the source code.

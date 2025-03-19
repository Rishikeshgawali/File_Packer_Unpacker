# File Packer Unpacker

**File Packer Unpacker** is a Java-based suite for managing file packing and unpacking operations. The system features a secure login interface, a user-friendly dashboard for packing and unpacking files, and a real-time clock display. The application is built using **Swing** for the graphical user interface (GUI), providing a smooth and interactive user experience.

## Features

- **Login System**: A secure login interface where users must enter a valid username and password.
- **File Packing**: A feature for packing files into compressed formats.
- **File Unpacking**: A feature for extracting packed files.
- **Real-Time Clock**: Displays the current date, time, and day in the header of the application window.
- **User Interface**: Interactive, with buttons to trigger actions like packing or unpacking files.
- **Security**: Only authorized users can access the file operations after successfully logging in.

## Components

### 1. **MarvellousLogin.java**
   - Provides the login screen with fields for entering a username and password.
   - Validates user credentials: username and password must each be at least 8 characters long.
   - After successful login, the user is taken to the next page where they can choose to pack or unpack files.

### 2. **NextPage.java**
   - This page appears after the user logs in, welcoming them and offering buttons to either "Pack Files" or "Unpack Files."
   - It allows the user to choose which action to perform after authentication.
   - The program will display relevant forms for packing and unpacking files when the user clicks the respective button.

### 3. **ClockLabel.java & Template.java**
   - These classes implement a real-time clock and date display in the GUI.
   - The **ClockLabel** class dynamically updates the current time, day, and date, showing them in the header section of the application.
   - **Template.java** provides a basic layout for the window, including clock functionality and buttons for window control (minimize/exit).

## Prerequisites

- Java Development Kit (JDK) 8 or higher.
- A Java IDE (e.g., IntelliJ IDEA, Eclipse, or NetBeans) or the command line for compiling and running.

## Installation

1. Repository:

    ```bash
    https://github.com/Rishikeshgawali/File_Packer_Unpacker
    ```

2. Navigate to the project directory and open it in your preferred Java IDE.

3. Compile the Java files:

    If you prefer using the command line:
    ```bash
    javac *.java
    ```

4. Run the **MarvellousMain** class to start the application:

    ```bash
    java MarvellousMain
    ```

## How to Use

1. **Login**: The login screen will prompt you for a username and password.
   - Use the following credentials for testing:
     - **Username**: `MarvelleousAdmin`
     - **Password**: `MarvelleousAdmin`

2. After logging in, you will be taken to the **NextPage**, where you can choose between packing or unpacking files.

3. **Pack Files**: Clicking "Pack Files" will trigger the packing functionality (implementation details to be added).
   
4. **Unpack Files**: Clicking "Unpack Files" will trigger the unpacking functionality (implementation details to be added).

5. **Exit and Minimize**: You can minimize or exit the application using the buttons in the header of the window.

## Code Walkthrough

### 1. **MarvellousLogin Class**
   - Manages the login process, validating credentials and transitioning to the next page if successful.

### 2. **NextPage Class**
   - Displays the options for packing or unpacking files after a successful login.
   - Handles button actions for packing and unpacking files.

### 3. **ClockLabel & Template Classes**
   - Provides real-time clock functionality for displaying the current date, time, and day in the header.
   - **Template.java** also handles window layout and basic controls like minimizing and exiting.

## Future Enhancements

- **File Packing/Unpacking**: Implement actual functionality to pack files into compressed formats and extract them.
- **User Registration**: Allow users to register with a username and password.
- **Password Security**: Improve password security (e.g., encrypting passwords or using a database for storage).
- **UI Enhancements**: Improve the graphical interface for a more modern and user-friendly experience.

## Author

- **RISHIKESH BHARAT GAWALI**

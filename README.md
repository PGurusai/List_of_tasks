**Instruction**

Java Task List Application Setup Instructions

For Windows:

1. Download and Install JDK:
   - Visit the Oracle JDK download page: [Oracle JDK Download](https://www.oracle.com/java/technologies/javase-downloads.html).
   - Download and install the appropriate JDK version for your Windows system.

2. Set Up Environment Variables (Optional but Recommended):
   - After installing the JDK, set up the `PATH` environment variable for easy access to Java commands.
     - Right-click on "This PC" or "My Computer" and select "Properties."
     - Click "Advanced system settings."
     - Click the "Environment Variables" button.
     - In the "System variables" section, find and select the "Path" variable.
     - Click "Edit" and add the path to the `bin` folder of your JDK installation. For example, `C:\Program Files\Java\jdk1.8.0_281\bin`.
     - Click "OK" to save your changes.

3. Compile and Run the Java Program:
   - Open Command Prompt.
   - Navigate to the directory where your `TaskListApp.java` file is located.
   - Compile the Java code using the `javac` command:
     ```
     javac TaskListApp.java
     ```
   - Run the program using the `java` command:
     ```
     java TaskListApp.java
     ```

For macOS:

1. Install Homebrew (if not already installed):
   - If you don't have Homebrew installed on your macOS, you can install it by opening the Terminal and running the following command:
     ```
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
     ```

2. Install JDK using Homebrew:
   - Once you have Homebrew installed, use it to install the JDK:
     ```
     brew tap adoptopenjdk/openjdk
     brew cask install adoptopenjdk8
     ```

3. Compile and Run the Java Program:
   - Open Terminal.
   - Navigate to the directory where your `TaskListApp.java` file is located.
   - Compile the Java code using the `javac` command:
     ```
     javac TaskListApp.java
     ```
   - Run the program using the `java` command:
     ```
     java TaskListApp
     ```

These instructions will help you compile and run your Java program on both Windows and macOS.

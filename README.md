# Calculator

### Overview
The Calculator Application is a Java-based tool designed to perform basic arithmetic operations. It utilizes Java Applets and Frames to provide a graphical user interface for user interaction. This project demonstrates the integration of Applets and Frames in Java to create a functional and user-friendly calculator.

### Features
- **Basic Arithmetic Operations**: Supports addition, subtraction, multiplication, and division.
- **User Interface**: Built using Java's AWT (Abstract Window Toolkit) and Swing components to provide a graphical interface for user interaction.
- **Applet Integration**: Incorporates Java Applets to embed the calculator into a web page or application.

### Technologies Used
- **Java**: Core programming language used for building the application.
- **AWT and Swing**: Java libraries used to create the graphical user interface components.
- **Applet**: Used to run the calculator within a web browser or applet viewer.

### Installation
1. Clone the repository: `git clone https://github.com/yourusername/calculator-app.git`
2. Navigate to the project directory: `cd calculator-app`
3. Compile the Java files: `javac *.java`
4. Run the application: 
   - For Applet: Use an Applet viewer or embed the Applet into an HTML file and open it in a browser.
   - For Frame: Run the main class using `java CalculatorFrame`.

### Usage
1. Launch the application using the preferred method (Applet or Frame).
2. Enter numbers and select the desired arithmetic operation.
3. Click the "=" button to perform the calculation and display the result.
4. Use the "C" button to clear the input fields.

### Example Applet HTML Integration
To embed the calculator as an Applet, use the following HTML snippet:
```html
<applet code="CalculatorApplet.class" width="300" height="400">
</applet>
```

### Contributing
Feel free to fork the repository and submit pull requests for improvements or additional features.

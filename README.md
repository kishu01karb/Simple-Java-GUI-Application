# Simple Java GUI Application

A basic Java Swing GUI application that demonstrates interactive components including text fields, buttons, and labels.

## Description

This is a simple graphical user interface application built with Java Swing. The application features a text input field where users can enter their name, and upon clicking the button, it displays a personalized greeting message.

## Features

- Text input field for user name entry
- Interactive button with click event handling
- Dynamic label that updates based on user input
- Clean and simple user interface

## Screenshots

**Initial State:**
- Empty text field ready for input
- "Click Me" button
- Default greeting message "Hello!"

**After Interaction:**
- Enter a name (e.g., "luna") in the text field
- Click the "Click Me" button
- Label updates to show "hello, luna!"

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Any Java IDE (Eclipse, IntelliJ IDEA, NetBeans) or command line

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Compile the Java file:
```bash
javac SimpleGUI.java
```

3. Run the application:
```bash
java SimpleGUI
```

## Usage

1. Launch the application by running the `SimpleGUI` class
2. A window titled "My First GUI" will appear
3. Type your name in the text field
4. Click the "Click Me" button
5. The label below will update with a personalized greeting

## Code Structure

```
SimpleGUI.java
├── JFrame (Main Window)
├── JTextField (Text Input)
├── JButton (Action Button)
└── JLabel (Display Label)
```

## How It Works

- The application creates a 300x150 pixel window
- Components are positioned using absolute positioning (`setLayout(null)`)
- An ActionListener is attached to the button that:
  - Reads text from the input field
  - Updates the label with "hello, [name]!"

## Technical Details

- **Framework:** Java Swing
- **Layout:** Absolute positioning with `setBounds()`
- **Event Handling:** Lambda expression for ActionListener
- **Window Size:** 300 x 150 pixels

## Future Enhancements

- Add input validation
- Implement layout managers for responsive design
- Add more interactive components
- Style the UI with custom colors and fonts

## License

This project is open source and available under the MIT License.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.


---

**Note:** This is a beginner-friendly project designed to demonstrate basic Java Swing concepts.

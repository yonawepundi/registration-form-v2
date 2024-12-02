# Form Registration Application

This is a simple Java Swing application for a registration form. Users can input their details such as name, mobile number, gender, date of birth, and address. The application includes a graphical user interface (GUI) with a table to display the submitted information.

## Features

- Input fields for:
  - Name
  - Mobile number
  - Gender (Male/Female)
  - Date of Birth (Day, Month, Year dropdowns)
  - Address
- Accept Terms and Conditions checkbox
- Buttons for:
  - Submit: Adds the input details to the table.
  - Reset: Clears all the input fields.
- Displays submitted data in a table format.
- Error handling for unaccepted terms and conditions.

## Prerequisites

- Java Development Kit (JDK) 8 or later
- IDE with support for Swing, e.g., NetBeans or IntelliJ IDEA

## How to Run

1. Clone this repository or download the project files.
2. Open the project in your preferred IDE.
3. Compile and run the `FormRegistration.java` file.
4. The application window will open, allowing you to input and submit registration details.

## Code Overview

The application is implemented using Java Swing components, including:
- JTextField: For name, mobile, and address inputs.
- JRadioButton: For gender selection.
- JComboBox: For date of birth selection.
- JTable: To display submitted data.
- JButton: To handle form submission and reset actions.
- Checkbox: For accepting terms and conditions.

### Main Components

- jTextField1, `jTextField2`, `jTextField3`: Input fields for name, mobile, and address.
- jRadioButton2, `jRadioButton3`: Radio buttons for gender selection.
- jComboBox1, `jComboBox2`, `jComboBox3`: Dropdowns for date of birth selection.
- jTable1: Table to display submitted details.
- jButton1: Submit button with event handling to add data to the table.
- jButton2: Reset button with event handling to clear the form.
- checkbox1: Checkbox for terms and conditions.

## File Structure

```plaintext
src/
└── FormRegistration.java

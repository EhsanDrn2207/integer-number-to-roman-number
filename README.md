
# **Integer to Roman Numeral Converter**

This is a Python application with a graphical user interface (GUI) built using Tkinter. The application allows users to convert integer numbers into Roman numerals. It handles various edge cases such as zero, negative numbers, and invalid inputs.

---

## **Features**
- Convert positive integers to Roman numerals.
- User-friendly interface with input fields and buttons.
- Error handling for invalid inputs:
  - Non-integer inputs.
  - Zero and negative numbers.
- Keyboard shortcuts:
  - Press "Enter" to perform the conversion.
  - Press "Q" to quit the application.

---

## **Installation**

### **Prerequisites**
- Python 3.x installed on your system.
- The following custom modules (provided separately):
  - `special_number`
  - `components_of_number`
  - `convert_number`
  - `errors`

### **Steps**
1. Clone or download this repository to your local machine.
2. Ensure the following files are in the same directory:
   - `special_number.py`
   - `components_of_number.py`
   - `convert_number.py`
   - `errors.py`
3. Install any dependencies, if required, for the custom modules.
4. Run the main script:
   ```bash
   python <script_name>.py
   ```
   Replace `<script_name>` with the name of the Python file containing the main code.

---

## **Usage**
1. Launch the application by running the script.
2. Enter a positive integer in the **"Integer number"** field.
3. Click the **"Change"** button or press **Enter**.
4. The Roman numeral equivalent of the entered integer will be displayed in the **"Roman number"** field.
5. To exit, click the **"Quit"** button or press **Q**.

---

## **Error Handling**
- **Non-integer input**: Displays the message "You must enter an integer number."
- **Zero input**: Displays the message "Invalid number."
- **Negative input**: Displays the message "You must enter a positive number."

---

## **Keyboard Shortcuts**
- **Enter**: Perform the conversion.
- **Q**: Quit the application.

---

## **Project Structure**
- **Main script**: Contains the GUI and the core application logic.
- **Modules**:
  - `special_number.py`: Handles "special" number logic for Roman numeral conversion.
  - `components_of_number.py`: Breaks down integers into components for Roman numeral representation.
  - `convert_number.py`: Converts integer components into Roman numerals.
  - `errors.py`: Custom error classes for zero and negative number handling.

---

## **Acknowledgements**
- Tkinter for GUI development.
- Python for being an awesome programming language!

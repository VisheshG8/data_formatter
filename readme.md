# **README: Data Formatter Script**

## **Overview**
This script processes a list of comma-separated strings containing Christmas-related words and formats them into a specific structure. The formatted output consists of uppercase words enclosed in double quotes and grouped within square brackets, suitable for further use in applications like games, quizzes, or displays.

---

## **Features**
- Converts words to **uppercase**.
- Removes unnecessary spaces around words.
- Formats the words as comma-separated strings enclosed in square brackets.
- Outputs the formatted data line by line for easy readability.

---

## **Input**
The input is a list of strings where:
- Each string contains comma-separated words or phrases.
- Example:
  ```python
  "Christmas Tree, Evergreen, Decorate, Holiday, Pine, Ornaments"
  ```

---

## **Output**
The script produces the following formatted output:
- Words are in **uppercase**.
- Words are wrapped in double quotes (`"`).
- Words are grouped within square brackets (`[` and `]`).
- Example:
  ```python
  ["CHRISTMAS TREE", "EVERGREEN", "DECORATE", "HOLIDAY", "PINE", "ORNAMENTS"],
  ```

---

## **Usage**

### **Requirements**
- Python 3.x installed on your machine.

### **Steps to Run the Script**
1. Copy the script into a `.py` file, e.g., `format_data.py`.
2. Run the script using Python:
   ```bash
   python format_data.py
   ```

### **Customization**
- Modify the `data` list at the top of the script to include your custom comma-separated strings.
  Example:
  ```python
  data = [
      "Example Word, Another Example, Test Data"
  ]
  ```

---

## **Script Explanation**
The script is divided into the following parts:
1. **Input Data**: A list of comma-separated strings.
2. **List Comprehension**: 
   - Processes each string to:
     - Split by commas.
     - Convert words to uppercase.
     - Strip extra spaces.
     - Wrap words in double quotes.
     - Group them with square brackets.
3. **Output**: Prints the formatted strings line by line.

---# **README: Christmas Data Formatter Script**

## **Overview**
This script processes a list of comma-separated strings containing Christmas-related words and formats them into a specific structure. The formatted output consists of uppercase words enclosed in double quotes and grouped within square brackets, suitable for further use in applications like games, quizzes, or displays.

---

## **Features**
- Converts words to **uppercase**.
- Removes unnecessary spaces around words.
- Formats the words as comma-separated strings enclosed in square brackets.
- Outputs the formatted data line by line for easy readability.

---

## **Input**
The input is a list of strings where:
- Each string contains comma-separated words or phrases.
- Example:
  ```python
  "Christmas Tree, Evergreen, Decorate, Holiday, Pine, Ornaments"
  ```

---

## **Output**
The script produces the following formatted output:
- Words are in **uppercase**.
- Words are wrapped in double quotes (`"`).
- Words are grouped within square brackets (`[` and `]`).
- Example:
  ```python
  ["CHRISTMAS TREE", "EVERGREEN", "DECORATE", "HOLIDAY", "PINE", "ORNAMENTS"],
  ```

---

## **Usage**

### **Requirements**
- Python 3.x installed on your machine.

### **Steps to Run the Script**
1. Copy the script into a `.py` file, e.g., `format_data.py`.
2. Run the script using Python:
   ```bash
   python format_data.py
   ```

### **Customization**
- Modify the `data` list at the top of the script to include your custom comma-separated strings.
  Example:
  ```python
  data = [
      "Example Word, Another Example, Test Data"
  ]
  ```

---

## **Script Explanation**
The script is divided into the following parts:
1. **Input Data**: A list of comma-separated strings.
2. **List Comprehension**: 
   - Processes each string to:
     - Split by commas.
     - Convert words to uppercase.
     - Strip extra spaces.
     - Wrap words in double quotes.
     - Group them with square brackets.
3. **Output**: Prints the formatted strings line by line.

---

## **Example**
### Input:
```python
data = [
    "Christmas Tree, Evergreen, Decorate, Holiday, Pine, Ornaments"
]
```

### Output:
```plaintext
["CHRISTMAS TREE", "EVERGREEN", "DECORATE", "HOLIDAY", "PINE", "ORNAMENTS"],
```

---

## **Customization and Extensions**
- **Add More Data**: Add additional strings to the `data` list to process multiple lines.
- **Save to File**: Modify the script to save the output to a `.txt` or `.csv` file.
- **Different Formatting**: Adjust the `join` or string formatting logic to produce variations in the output structure.

---

## **Author**
This script was written with simplicity and reusability in mind. If you have any questions or need further customization, feel free to ask! 😊

## **Example**
### Input:
```python
data = [
    "Christmas Tree, Evergreen, Decorate, Holiday, Pine, Ornaments"
]
```

### Output:
```plaintext
["CHRISTMAS TREE", "EVERGREEN", "DECORATE", "HOLIDAY", "PINE", "ORNAMENTS"],
```

---

## **Customization and Extensions**
- **Add More Data**: Add additional strings to the `data` list to process multiple lines.
- **Save to File**: Modify the script to save the output to a `.txt` or `.csv` file.
- **Different Formatting**: Adjust the `join` or string formatting logic to produce variations in the output structure.

---

## **Author**
This script was written with simplicity and reusability in mind. If you have any questions or need further customization, feel free to ask! 😊
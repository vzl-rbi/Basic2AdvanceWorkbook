# Day-01

what is excell, workbook in Excell, workshell, Rows in Excell, Columns in Excells, Cell, Cell address, formula, function, range in excell ?

# **Excel Basics for Data Analytics - Class Notes**

## **Microsoft Excel**

A spreadsheet software developed by Microsoft used for data organization, calculation, analysis, and visualization. It's a fundamental tool for data analytics.

## **Key Components of Excel:**

### **1. Workbook**

- The main Excel file (with .xlsx extension)
- Can contain multiple worksheets
- **Example:** "Sales_Report_2024.xlsx" is a workbook

### **2. Worksheet**

- A single page/spreadsheet within a workbook
- Default names: Sheet1, Sheet2, Sheet3
- Can be renamed, added, deleted, or moved
- **Shortcut:** Click `+` button near sheet tabs to add new worksheet

### **3. Rows**

- Horizontal lines in a worksheet
- Identified by numbers (1, 2, 3, ... up to 1,048,576)
- Each row represents a record/entry in data analytics

### **4. Columns**

- Vertical lines in a worksheet
- Identified by letters (A, B, C, ... up to XFD = 16,384 columns)
- Each column represents a field/variable in data analytics

### **5. Cell**

- The intersection of a row and column
- Basic unit where data is entered
- Can contain: text, numbers, dates, formulas, functions

### **6. Cell Address/Reference**

- Unique identifier of a cell using column letter + row number
- **Examples:**
  - `A1` = Column A, Row 1
  - `D15` = Column D, Row 15
  - `$A$1` = Absolute reference (won't change when copied)

### **7. Formula**

- An expression that calculates values
- Always starts with `=` (equal sign)
- Can include numbers, cell references, operators (+, -, \*, /, ^)
- **Examples:**
  - `=A1+B1` (Adds values in A1 and B1)
  - `=C5*0.18` (Multiplies C5 by 0.18)

### **8. Function**

- Predefined formulas in Excel
- Perform specific calculations using arguments in parentheses
- **Basic Structure:** `=FUNCTION_NAME(argument1, argument2, ...)`
- **Common Functions for Data Analytics:**
  - `=SUM(A1:A10)` - Adds all numbers in the range
  - `=AVERAGE(B2:B20)` - Calculates average
  - `=COUNT(C1:C100)` - Counts numeric entries
  - `=MAX(D:D)` - Finds highest value
  - `=MIN(E:E)` - Finds lowest value

### **9. Range**

- A selection of two or more cells
- **Notation:** FirstCell:LastCell
- **Examples:**
  - `A1:A10` - Column A, rows 1 through 10
  - `B2:D5` - Rectangular block from B2 to D5
  - `A:A` - Entire column A
  - `1:1` - Entire row 1

---

## **Data Analytics Application:**

- **Rows** = Individual records/observations (e.g., each customer's data)
- **Columns** = Variables/attributes (e.g., customer name, age, purchase amount)
- **Formulas/Functions** = For calculations, aggregations, and transformations
- **Ranges** = To select data for analysis, charts, or functions

## **Quick Reference:**

```
Workbook → File
Worksheet → Page in file
Rows → Horizontal (numbers)
Columns → Vertical (letters)
Cell → Single box
Cell Address → Column+Row (B5)
Formula → Custom calculation (starts with =)
Function → Built-in formula (SUM, AVERAGE)
Range → Group of cells (A1:C10)
```

# **Excel Shortcut Keys - Quick Reference**

## **Navigation Shortcuts**

### **CTRL + Arrow Keys (Jump to Edge)**

- **CTRL + →** : Jump to last filled cell to the right in current row
- **CTRL + ←** : Jump to last filled cell to the left in current row
- **CTRL + ↓** : Jump to last filled cell downward in current column
- **CTRL + ↑** : Jump to last filled cell upward in current column

### **Worksheet Navigation**

- **CTRL + Page Up** : Move to previous worksheet
- **CTRL + Page Down** : Move to next worksheet

## **Zoom Shortcuts**

- **CTRL + Mouse Scroll** : Zoom in/out

_Note: There's no universal Ctrl + shortcut for zoom in/out in Excel. Use the status bar zoom slider or Alt+W+Q._

## **Workbook Management**

### **Save Operations**

- **CTRL + S** : Save workbook (quick save)
- **F12** : Save As (open Save As dialog)
- **CTRL + SHIFT + S** : Save As (alternative)
- **ALT + F, then A** : Save As (via File menu)

### **Close Operations**

- **CTRL + W** : Close current workbook

## **Pro Tip for Data Analytics:**

- Use **CTRL + Arrow Keys** to quickly navigate large datasets
- Use **CTRL + SHIFT + Arrow Keys** to select entire data ranges for functions
- **CTRL + S** frequently to avoid data loss!
- **CTRL + W** when done with a workbook (Excel will prompt to save)

## **Practice Exercise:**

Open a sample dataset and try:

1. Navigate to the last row using CTRL+↓
2. Select the entire column using CTRL+SHIFT+↓
3. Switch between sheets with CTRL+Page Down
4. Save with CTRL+S
5. Close with CTRL+W

# Day-2

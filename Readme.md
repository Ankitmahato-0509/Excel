# Stuff I Learn About Excel for Reference

This repository contains my **personal notes and practice files on Excel**.
Each section includes the **Excel file name and a screenshot of the output for quick reference**.


## 01. Basic Formulas

**File:** `01.Basic Formulas.xlsx`

### Concepts Covered:

* Addition, subtraction, and multiplication
* Working with multiple cells
* Total, subtotal, and grand total calculations
* Tax calculation using percentages
* Basic spreadsheet formatting

### Screenshots:

#### Item Spreadsheet:

![Item Spreadsheet](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-04-04%20215344.png?raw=true)

#### Student Weight Calculations:

![Student Weight](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-04-04%20215323.png?raw=true).



## 02. Autofill

**File:** `02.Autofill.xlsx`

### Concepts Covered:

* Automatically filling number sequences (1, 2, 3…)
* Filling days of the week (Sun to Sat)
* Filling months of the year (Jan to Dec)
* Using the fill handle (drag feature)
* Copying values versus extending a series
* Autofill options (Copy Cells, Fill Series, etc.)
* Improving efficiency in repetitive data entry

### Screenshot:

![Autofill](https://github.com/Ankitmahato-0509/Excel/blob/7a621e7dd1b7be3b313dac7af323dd0c74449c2a/images/Screenshot%202026-03-06%20141634.png)



## 03. Find & Replace

**File:** `03.Find & Replace.xlsx`

### Concepts Covered:

* Using **Find (Ctrl + F)** to search for data
* Using **Replace (Ctrl + H)** to modify values
* Replacing text across an entire dataset
* Bulk updating repeated entries (e.g., Marketing to Research & Development)
* Case-sensitive search options
* Replacing specific values or all occurrences
* Maintaining data consistency efficiently

### Screenshots:

#### Before Apply:

![Before Apply](https://github.com/Ankitmahato-0509/Excel/blob/5412bbf93ec9672c37c55a5974ada167b47d5a23/images/Screenshot%202026-03-06%20141717.png)

#### After Apply:

![After Apply](https://github.com/Ankitmahato-0509/Excel/blob/5412bbf93ec9672c37c55a5974ada167b47d5a23/images/Screenshot%202026-03-06%20141738.png)



## 04. Text Function & Sorting Data

**File:** `Text Function & Sorting Data.xlsx`

### Concepts Covered:

* Using text functions: UPPER(), LOWER(), PROPER(), LEN()
* Extracting text using LEFT(), RIGHT(), MID()
* Combining text using CONCAT() / &
* Cleaning data using TRIM()
* Using Text to Columns feature
* Transposing data (rows ↔ columns)
* Sorting data (A–Z, Z–A, multi-level sorting)

### Screenshots:

![Text Functions](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-04-04%20224440.png?raw=true)

![Trim Function](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-04-04%20224522.png?raw=true)

![Transpose Function](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-04-04%20224543.png?raw=true)

![Text to Column](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-04-04%20224558.png?raw=true)



## 05. Cell Referencing (Relative, Absolute & Mixed)

**File:** `05.Cell Referencing.xlsx`

### Concepts Covered:

* Understanding cell referencing in Excel
* Difference between Relative, Absolute, and Mixed references
* Using `$` to lock rows and/or columns
* Copying formulas without breaking references
* Practical use cases in calculations
* Improving accuracy in large datasets



### Relative Referencing

* Automatically adjusts when copied
* Example: `=A1+B1 → =A2+B2`

Screenshot:


![Relative Referencing](https://github.com/Ankitmahato-0509/Excel/blob/535c254f92e19d6c8d94aa4332873cae07167f70/images/Screenshot%202026-04-06%20232021.png?raw=true).





### Absolute Referencing

* Fixed reference using `$`
* Example: `=$B$3`

Screenshot:


![Absolute Referencing](https://github.com/Ankitmahato-0509/Excel/blob/9faa8d961625cda85c9c1880df1081dbe0faccb5/images/Screenshot%202026-04-06%20232109.png?raw=true).




### Mixed Referencing

* Combination of relative and absolute
* `$A1` → column fixed
* `A$1` → row fixed

Screenshot:


![Mixed Referencing](https://github.com/Ankitmahato-0509/Excel/blob/9faa8d961625cda85c9c1880df1081dbe0faccb5/images/Screenshot%202026-04-06%20232135.png?raw=true).



### Electricity Bill Example

* Units Used = Present − Previous
* Units Charge = Units × Unit Cost
* Amount = Charge + Standing Charge

Screenshot:


![Electricity Bill](https://github.com/Ankitmahato-0509/Excel/blob/9faa8d961625cda85c9c1880df1081dbe0faccb5/images/Screenshot%202026-04-06%20232156.png?raw=true).


# 06. Data Validation

**File:** `06.Data Validation.xlsx`

### Concepts Covered:

* Restricting user input using **Data Validation**
* Allowing only **whole numbers within a specified range**
* Creating **drop-down lists** for predefined values
* Displaying **Input Messages** to guide users
* Showing **Error Alerts** for invalid entries
* Improving data accuracy and consistency
* Preventing incorrect or unwanted data entry

### Example Demonstration

This worksheet compares data entry **with and without Data Validation** to demonstrate how validation helps maintain clean and consistent data.

Without Data Validation:
- Users can enter any value, including invalid data.
- Different formats and inconsistent entries may occur.

With Data Validation:
- Only permitted values can be entered.
- Input messages guide users before entering data.
- Error alerts prevent invalid entries.

### Screenshot

![Data Validation Demo](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-06%20231700.png?raw=true)


## Data Validation Exercises

This worksheet contains practical exercises to reinforce Data Validation concepts.

### Exercises Covered

**Whole Number Validation**

* Accept only whole numbers from **1 to 10**
* Display a custom **Input Message**
* Show an **Error Alert** when invalid values are entered

**Drop-down List Validation**

* Create a **Gender** drop-down list containing:
  * Male
  * Female

**Colour List Validation**

* Create a drop-down list of predefined colours.
* Restrict users to selecting only values from the list.

These exercises demonstrate how Data Validation improves data quality and provides a better user experience during data entry.

### Screenshot

![Data Validation Exercises](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-06%20231753.png?raw=true)


# 07. Conditional Formatting

**File:** `07.Conditional Formatting.xlsx`

### Concepts Covered:

* Highlighting cells based on specified conditions
* Using **Greater Than**, **Less Than**, and **Between** rules
* Applying **Color Scales** to visualize value ranges
* Using **Data Bars** to compare values visually
* Applying **Icon Sets** to represent performance
* Formatting dates based on custom conditions
* Improving data visualization without modifying the original values

---

## Example Demonstration

This worksheet introduces the basics of **Conditional Formatting** by automatically highlighting values that satisfy predefined rules.

### Examples:

- Highlight values **greater than 7**
- Automatically apply formatting when conditions are met
- Improve readability by emphasizing important values

### Screenshot

![Conditional Formatting](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-07%20223728.png?raw=true)

---

## Exercise 1 – Date-Based Conditional Formatting

This exercise demonstrates how to apply Conditional Formatting to dates using multiple conditions.

### Rules Applied

- Dates **greater than 01-Sep-2007** → **Green**
- Dates **between 01-May-2007 and 01-Sep-2007** → **Blue**
- Dates **less than 01-May-2007** → **Red**

### Skills Learned

- Formatting dates using conditional rules
- Applying multiple rules to the same range
- Visual categorization of date values

### Screenshot

![CF Exercise 1](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-07%20223640.png?raw=true)

---

## Exercise 2 – Data Bars & Color Scales

This exercise demonstrates two popular Conditional Formatting features used in dashboards and reports.

### Data Bars

- Display relative values using horizontal bars inside cells.
- Quickly compare numeric values without creating charts.

### Color Scales

- Apply gradient colors based on cell values.
- Higher values appear with stronger colors while lower values use lighter colors.

### Skills Learned

- Visual comparison of numerical data
- Identifying high and low values instantly
- Enhancing dashboards with built-in visual indicators

### Screenshot

![CF Exercise 2](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-07%20223658.png?raw=true)

---

## Exercise 3 – Icon Sets

This exercise demonstrates how **Icon Sets** can visually represent employee performance.

### Skills Learned

- Applying directional arrow icons
- Representing performance using visual indicators
- Improving report readability with icons

### Screenshot

![CF Exercise 3](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-07%20223714.png?raw=true)


# 08. Sorting & Filtering

**File:** `8.Sorting & Filtering.xlsx`

### Concepts Covered

* Sorting data in Ascending (A–Z / Smallest to Largest) order
* Sorting data in Descending (Z–A / Largest to Smallest) order
* Performing multi-level sorting using multiple columns
* Using Auto Filter to display specific records
* Filtering text, numbers, and dates
* Applying Number Filters (Greater Than, Less Than, Between)
* Using Advanced Filter for complex filtering conditions
* Improving data analysis by displaying only relevant information

---

## Sorting

Sorting is the process of arranging data into a meaningful order, making it easier to organize, compare, and analyze information. Data can be sorted alphabetically, numerically, or by date in either ascending or descending order.

### Screenshot

![Sorting](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-26%20224009.png?raw=true)

---

## Filtering

Filtering allows you to display only the records that meet specific criteria while temporarily hiding the remaining data. This helps you quickly focus on the information you need without changing the original dataset.

### Screenshot

![Filtering](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-26%20224023.png?raw=true)

---

## Exercise 1 – Show Sales of MegaMart

This exercise demonstrates how to filter data to display sales records for the **MegaMart** customer only.

### Skills Learned

* Using Auto Filter
* Filtering records by customer name
* Displaying customer-specific sales data

### Screenshot

![Exercise 1](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-26%20224034(1).png?raw=true)

---

## Exercise 2 – Show MegaMart Sales for Cookies

This exercise filters the dataset to display only sales where the **Customer is MegaMart** and the **Product is Cookies**.

### Skills Learned

* Applying multiple filter conditions
* Filtering by customer and product
* Viewing targeted sales records

### Screenshot

![Exercise 2](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-26%20224044.png?raw=true)

---

## Exercise 3 – Show Sales Between $1,000 and $1,500

This exercise uses **Number Filters** to display sales whose total amount falls between **$1,000** and **$1,500**.

### Skills Learned

* Using the Between number filter
* Filtering numeric values within a range
* Analyzing mid-range sales transactions

### Screenshot

![Exercise 3](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-26%20224054.png?raw=true)

---

## Exercise 4 – Show Milk Sales Greater Than $1,000

This exercise filters records where the **Product is Milk** and the **Total Sales are greater than $1,000**.

### Skills Learned

* Combining text and number filters
* Using the Greater Than filter
* Filtering product-specific sales

### Screenshot

![Exercise 4](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-26%20224109.png?raw=true)

---

## Exercise 5 – Advanced Filter (MegaMart Cookies & MiniMart Milk)

This exercise demonstrates the use of **Advanced Filter** to retrieve records matching multiple criteria:

* MegaMart sales for Cookies
* MiniMart sales for Milk

### Skills Learned

* Using Advanced Filter
* Applying multiple OR conditions
* Filtering complex datasets

### Screenshot

![Exercise 5](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-26%20224125.png?raw=true)

---

## Exercise 6 – Advanced Filter with Multiple Conditions

This exercise demonstrates advanced filtering using different conditions simultaneously.

### Filter Conditions

* MiniMart sales for **Cookies** where Total Sales are **greater than $2,000**
* MiniMart sales for **Milk** where Total Sales are **less than $1,000**

### Skills Learned

* Advanced Filter with AND/OR logic
* Applying multiple criteria
* Solving real-world filtering scenarios

### Screenshot

![Exercise 6](https://github.com/Ankitmahato-0509/Excel/blob/main/images/Screenshot%202026-07-26%20224135.png?raw=true)

---



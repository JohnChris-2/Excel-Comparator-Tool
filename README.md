# Excel-Comparator-Tool
Excel Comparator Tool is a Python-based application that compares two Excel files using unique columns as keys. It highlights differences, calculates variances, and applies conditional formatting to help users easily identify mismatches between datasets.

Read below for a Detailed Description ----

Excel Comparator Tool 🧮📊
The Excel Comparator Tool is a Python-powered application designed to simplify and automate the comparison of two Excel files. Whether you're dealing with large datasets or auditing data from different sources, this tool helps users efficiently compare Excel sheets based on unique key columns, identify mismatches, calculate differences, and highlight discrepancies using conditional formatting.

🔍 Key Features
✅ Unique Column Matching: Select one or more unique key columns to align data rows accurately across both files.

📊 Value Comparison: Automatically detects and compares differences in matching rows across all columns.

✨ Conditional Formatting: Highlights mismatches directly in the Excel output file for clear visibility.

📈 Difference Calculation: Shows the numerical difference for applicable columns (e.g., quantities, values).

💾 Excel Output: Generates a new Excel file with comparison results, difference columns, and color-coded formatting.

⚡ Efficient for Large Datasets: Built using Pandas and OpenPyXL to handle large Excel files with high performance.

🛠️ Technologies Used
Python 3.x

Pandas – for data manipulation and comparison logic

OpenPyXL – for editing Excel files and applying conditional formatting

(Optional): Flask – if building a web interface

🚀 How It Works
Upload or input two Excel files.

Select the unique key columns to align data (e.g., ID, Product Code).

The tool matches rows from both files using the selected keys.

It compares each column’s values and highlights mismatches:

Cells with differing values are highlighted in red.

Rows missing in one of the files can be highlighted in yellow/gray.

A new Excel file is generated with comparison results, including any calculated differences.

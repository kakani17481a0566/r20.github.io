# SRGEC R23 BATCH INTERNAL MARKS CALCULATOR

## Description

The **Seshadri Rao Gudlavalleru Engineering College (SRGEC) R23 BATCH INTERNAL MARKS CALCULATOR** is a web-based application designed to help students and faculty of SRGEC easily calculate their internal marks. The calculator accepts inputs for Midterm Marks, MCQ Marks, and Assignment Marks from two cycles and computes the final internal marks based on these inputs. It also provides options to export the results as a CSV or PDF report.

## Features

- **Input Fields** for:
  - Midterm Marks (MID1, MID2)
  - MCQ Marks (MCQ1, MCQ2)
  - Assignment Marks (Assign1, Assign2)

- **Validation**: The application ensures that each input value is within its valid range:
  - MID1, MID2: 0-30
  - MCQ1, MCQ2: 0-10
  - Assign1, Assign2: 0-5

- **Calculation of Internal Marks**: 
  - The application calculates the average of Midterm, MCQ, and Assignment Marks, and computes the total internal marks.

- **Export Options**:
  - **Export to CSV**: Save the input values and the calculated total marks as a CSV file.
  - **Export to PDF**: Download a detailed report in PDF format with a breakdown of the marks.

- **Error Handling**: Displays error messages if any input is out of range and highlights the invalid fields.

- **Reset Function**: Clears all inputs and results when the reset button is pressed.

## Technologies Used

- **HTML**: For the structure of the webpage.
- **CSS**: For styling the page and making the form elements user-friendly.
- **JavaScript**: For the logic to handle calculations, validation, and exporting results.
  - **jsPDF**: A library used to generate PDF reports.
  - **jsPDF-AutoTable**: A plugin for generating tables in PDFs.
  - **Bootstrap 4**: A CSS framework used for responsive design and UI components.

## How to Use

1. **Enter Marks**:
   - Fill in the fields for MID1, MID2, MCQ1, MCQ2, Assign1, and Assign2.

2. **Calculate Internal Marks**:
   - Click the **"Calculate Internal Marks"** button to compute your marks. The results will be displayed below the input form with a breakdown of each category.

3. **Export Results**:
   - After calculating the marks, you can export the results:
     - Click **"Export to CSV"** to download a CSV file.
     - Click **"Export to PDF"** to download a PDF report.

4. **Reset**:
   - Click the **"Reset"** button to clear all inputs and results.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/r23.github.io.git

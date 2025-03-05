# SRGEC Internal Marks Calculator (R23 & R20)

This web application helps SRGEC students calculate their internal marks based on marks entered for midterms, MCQs, and assignments. It supports both R23 and R20 batches. The application provides the following features:
- Inputs for Midterm 1, Midterm 2, MCQ 1, MCQ 2, Assignment 1, and Assignment 2.
- Calculates average marks for each category and the total internal marks.
- Provides options to export the result to CSV or PDF format.

## Features

- **Input Fields**:
  - **Midterm Marks**: MID1 (0-30), MID2 (0-30)
  - **MCQ Marks**: MCQ1 (0-10), MCQ2 (0-10)
  - **Assignment Marks**: Assignment 1 (0-5), Assignment 2 (0-5)

- **Result Calculation**:
  - Displays the average for midterm marks, MCQs, and assignments.
  - Calculates total internal marks based on the averages.

- **Export Options**:
  - **Export to CSV**: Download the marks data and total in CSV format.
  - **Export to PDF**: Download a detailed report in PDF format.

- **Input Validation**:
  - Ensures that entered marks are within the specified ranges.
  - Highlights invalid inputs with red borders.

## Pages in This Project

### 1. **R23 Marks Calculator**

The `R23.html` page is designed for SRGEC R23 Batch students. It allows users to input marks for Midterm 1, Midterm 2, MCQ 1, MCQ 2, Assignment 1, and Assignment 2. After entering the data, the app will calculate the average marks for each category (midterm, MCQ, assignments) and display the total internal marks.

- **Result**: Once the data is entered, users can calculate their internal marks and view the result in a detailed table format.
- **Export Options**: After calculating the marks, users can export the results to CSV or PDF.

### 2. **R20 Marks Calculator**

The `R20.html` page is similar to the `R23.html` page but is designed for SRGEC R20 Batch students. The major difference is in the assessment structure and calculation method, which may differ slightly based on the R20 curriculum.

- **R20-specific calculation**: Based on the input data for Midterm 1, Midterm 2, MCQ 1, MCQ 2, Assignment 1, and Assignment 2, the app calculates the internal marks based on the R20 assessment format.
- **Navigation**: The user can navigate between `R23.html` and `R20.html` using buttons in the navigation bar.

## Screenshots

- **Home Page**: 
  Displays the calculator interface where users input their marks and calculate the results.
  
- **Result**: 
  After clicking the "Calculate Internal Marks" button, the application displays a detailed table of the results.

## How to Use

1. **Open the Application**:
   Open the `R23.html` or `R20.html` file in your web browser.

2. **Enter Marks**:
   Input the marks for the following fields:
   - Midterm 1: (0-30)
   - Midterm 2: (0-30)
   - MCQ 1: (0-10)
   - MCQ 2: (0-10)
   - Assignment 1: (0-5)
   - Assignment 2: (0-5)

3. **Click "Calculate Internal Marks"**:
   After entering all marks, click the "Calculate Internal Marks" button. The application will show:
   - Average for Midterm Marks, MCQ Marks, and Assignment Marks.
   - Total Internal Marks.

4. **Export Data**:
   After the calculation, you can export the data:
   - **CSV**: Download the data in CSV format.
   - **PDF**: Download a detailed PDF report with a table of results.

5. **Reset**: 
   Click the "Reset" button to clear all fields and start over.

## Files in This Project

- **R23.html**: Main HTML file that contains the structure and JavaScript logic for calculating R23 batch marks.
- **R20.html**: Main HTML file that contains the structure and JavaScript logic for calculating R20 batch marks.
- **index.css**: Custom CSS for styling the page.
- **External Libraries**:
  - Bootstrap 4.6.2 (for responsive design and layout).
  - jsPDF (for PDF export functionality).
  - jsPDF-AutoTable plugin (for table formatting in PDFs).

## Technologies Used

- **HTML5**: For the structure of the webpage.
- **CSS3**: For styling the page.
- **JavaScript**: For performing calculations and handling user interactions.
- **Bootstrap 4**: For responsive layout and design.
- **jsPDF**: To generate PDF reports.
- **jsPDF-AutoTable**: To render tables in the PDF format.

## How to Run Locally

To run this project locally, you don’t need any backend or server setup. You can simply open the HTML file in a browser.

### Steps:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/internal-marks-calculator.git

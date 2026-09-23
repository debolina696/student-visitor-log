# Student Entry & Exit Visitor Portal

A dynamic, web-based student visitor tracking system built with HTML, Tailwind CSS, and JavaScript. This project allows institutions to track student attendance and entry/exit logs while dynamically exporting structured data into 12 monthly sheets in Microsoft Excel format.

**Author**: Debolina Sorkhel

## Features
- **Validation**:
  - Enforces mandatory fields across all entries.
  - Strict 10-digit phone number format validation.
- **Form Controls**:
  - Class options restricted to Class 9 and Class 11.
  - Dynamic stream selection (Science, Arts, Commerce).
  - Choice of Entry or Exit status tracking.
- **Excel Export**:
  - Automatically routes entries into their respective month's tab sheet (Jan–Dec).
  - Handles automatic year-end file rollover.
  - Generates multi-tab `.xlsx` workbooks powered by SheetJS.
- **Search & Filter**: Real-time filtering by Name, Student ID, or Stream.

## Technologies Used
- HTML5
- Tailwind CSS
- JavaScript (ES6)
- [SheetJS](https://sheetjs.com/) for Excel export

## How to Run
1. Visit the live demo: [Student Entry & Exit Portal](https://debolina696.github.io/student-visitor-log/)
2. Fill out the form fields and submit an entry.
3. Use the **Export Current Month to Excel** button to download your logs in `.xlsx` format.

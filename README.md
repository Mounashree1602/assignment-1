# Google Sheets Clone

A web-based spreadsheet application that mimics the core functionalities of Google Sheets. It includes support for mathematical functions, data quality functions, basic chart generation, and local storage for saving and loading spreadsheets.

## Features

### Spreadsheet Interface
- Google Sheets-like UI with a grid structure.
- Supports drag-and-drop for cell content and formulas.
- Basic cell formatting (bold, italics, font size, color).
- Ability to add, delete, and resize rows and columns.

### Mathematical Functions
- `SUM(range)`: Calculates the sum of a range of cells.
- `AVERAGE(range)`: Computes the average of a range of cells.
- `MAX(range)`: Returns the maximum value from a range of cells.
- `MIN(range)`: Returns the minimum value from a range of cells.
- `COUNT(range)`: Counts the number of numeric values in a range.

### Data Quality Functions
- `TRIM(text)`: Removes leading and trailing spaces from a string.
- `UPPER(text)`: Converts text to uppercase.
- `LOWER(text)`: Converts text to lowercase.
- `REMOVE_DUPLICATES(range)`: Removes duplicate rows from a selection.
- `FIND_AND_REPLACE(range, find, replace)`: Finds and replaces text in a selection.

### Data Entry & Validation
- Supports different data types (numbers, text, dates).
- Basic validation to ensure numeric inputs in number cells.

### Additional Features
- Save and load spreadsheets using **local storage**.
- Basic **data visualization** using bar charts.
- Real-time updates for cell dependencies.

## Tech Stack
- **React**: UI development
- **react-data-grid**: Spreadsheet grid functionality
- **mathjs**: Mathematical expression evaluation
- **@mui/material**: UI components
- **chart.js & react-chartjs-2**: Data visualization

## Installation & Setup

1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/google-sheets-clone.git
   cd google-sheets-clone
   ```

2. **Install Dependencies**
   ```sh
   npm install
   ```

3. **Start the Development Server**
   ```sh
   npm start
   ```

4. Open `http://localhost:3000` in your browser.

## Usage
- Enter data into cells and use formulas by typing `=SUM(A1:A5)`.
- Click **Save** to store the spreadsheet locally.
- Click **Load** to retrieve saved data.
- Click **Generate Chart** to create a bar chart from data.




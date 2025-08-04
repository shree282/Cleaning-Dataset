
# Task 1: Data Cleaning Summary (Microsoft Excel)

As part of the data cleaning and preprocessing task, I worked with a customer marketing dataset and applied several essential data transformation techniques using Excel. The goal was to prepare the data for structured analysis by addressing formatting inconsistencies, column clarity, and overall dataset structure.

## 🛠️ Tools & Functions Used

- **Text to Columns**  
  Utilized Excel's delimiter-based split function to correctly separate values into individual columns for better accessibility and analysis.

- **Column Renaming & Reorganization**  
  Standardized column names such as `Kidhome`, `Teenhome`, and `Dt_Customer` to `kid_home`, `teen_home`, and `enrolment_date` respectively, ensuring clarity and consistency. Columns were also rearranged to improve logical flow and usability.

- **Remove Duplicates**  
  Applied Excel’s duplicate removal tool to eliminate repeated records, preserving data accuracy.

- **Handling Missing Values**  
  Identified and replaced blank cells with `"N/A"` using Go To Special and `Ctrl+Enter`, then aligned values properly using Find & Select with custom formatting.

- **Date Formatting**  
  Converted the `enrolment_date` column to a consistent `DD-MM-YYYY` format using Excel's cell formatting tools.

- **Numeric Formatting**  
  Applied 1,000s separators and number formatting to financial and transaction-related fields for better readability.

- **Sorting by ID**  
  Sorted the entire dataset in ascending order based on `customer_id` to ensure row consistency and enable easier referencing.

- **Visual Enhancements**  
  Center-aligned year-related fields (e.g., `year_birth`) and inserted spacing rows for better visual structure and presentation.

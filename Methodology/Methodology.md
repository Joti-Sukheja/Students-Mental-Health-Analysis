# 1. Data Cleaning in Excel

The steps were performed to clean the raw dataset before analysis:

1. **Handled Missing Values**:
   - Checked for any missing values in the dataset.
   - Replaced missing or null entries in critical columns with appropriate values (e.g., averages, placeholders, or "Not Specified").

2. **Standardized Columns**:
   - Renamed ambiguous column names for better clarity (e.g., "AgeGrp" renamed to "Age Group").
   - Ensured consistent formatting for text columns (e.g., converted all text to lowercase or proper case).

3. **Filtered Outliers**:
   - Removed outliers from numerical data such as ages or survey responses that were invalid or out of range.

4. **Categorized Data**:
   - Binned continuous data into categories (e.g., grouping ages into "18-20", "21-23", etc.).
   - Created new categorical columns, such as "Depression Level" based on numerical thresholds.

5. **Formatted Data Types**:
   - Converted numerical columns to the correct data types (e.g., integers or decimals).
   - Reformatted dates into a consistent format (DD/MM/YYYY).

6. **Added Derived Columns**:
   - Calculated new columns such as "High Depression Rate" using formulas (e.g., percentage calculations).

7. **Removed Duplicates**:
   - Eliminated duplicate rows to ensure the dataset's integrity.

---

# 2. Dashboard Creation in Excel

After cleaning the data, the following steps were performed to create the dashboard:

1. **Data Preparation for Visualizations**:
   - Created PivotTables for key metrics, such as depression levels by gender, age, and other categories.
   - Used formulas to calculate percentages, trends, and other derived values.

2. **Visualization Design**:
   - Designed charts, including bar charts, pie charts, and line charts, to represent data trends effectively.
   - Used conditional formatting to highlight significant insights (e.g., high depression levels).

3. **Dashboard Layout**:
   - Arranged visual elements in a clear and visually appealing manner.
    - Ensured that all visualizations and metrics were easy to interpret.

4. **Styling and Formatting**:
   - Applied consistent color schemes and fonts to ensure professional presentation.
   - Added titles and labels to all charts for clarity.

---

By following these steps, the dataset was transformed into meaningful insights, as shown in the attached screenshot.
![students_mental_health_analysis_Dashboard](./dashboard/Students%20mental%20health%20dashboard%20screenshot.png)


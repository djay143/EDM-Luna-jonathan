# Mid term Lab Task 3. Creating PIVOT TABLE and DASHBOARD

### Step 1: Prepare Your Data
- **Worksheet on Uncleaned DS Jobs**: You’ll need to clean and transform the data into a more usable format for analysis. Ensure that the data contains columns for roles, states, company size, sector, and salary.
- **Transform Tables**: You'll be using the following transformed tables to summarize the data:
  - **Sal By Role**: A table showing the average salary by job role.
  - **Sal By State**: A table summarizing the average salary by state.
  - **Sal by Size**: A table summarizing the average salary by company size.

### Step 2: Design the Dashboard
Once the data is cleaned and transformed, you can start designing the dashboard. Below are the specific elements that should be included:

#### 1. **State with the Most Data Science Jobs**
To determine the state with the most data science jobs, you’ll create a pivot table:
- **Pivot Table**: Rows = State, Values = Count of Data Science Jobs
- **Chart**: Create a bar chart or a pie chart to visualize which state has the most data science jobs.

#### 2. **Job Role with the Highest Average Salary**
Create a pivot table for job roles:
- **Pivot Table**: Rows = Job Role, Values = Average Salary (use the "Sal By Role" table)
- **Chart**: Create a bar or column chart to highlight the job role with the highest average salary.

#### 3. **Which Company Size Pays the Highest**
Create a pivot table for company size:
- **Pivot Table**: Rows = Company Size, Values = Average Salary (use the "Sal by Size" table)
- **Chart**: A bar or column chart showing the company size that pays the highest average salary.

#### 4. **Which Sector Employs the Most and Least Data Science Jobs**
For this, you'll need to create a pivot table with sectors and the count of data science jobs:
- **Pivot Table**: Rows = Sector, Values = Count of Jobs
- **Chart**: Create a bar or pie chart to show which sector employs the most and least data science jobs.

#### 5. **Which Sector Has the Minimum and Maximum Average Salary**
- **Pivot Table**: Rows = Sector, Values = Average Salary (this can be created using a pivot table on the salary data)
- **Chart**: A column or bar chart will show the sectors with the minimum and maximum average salaries.

#### 6. **PIVOT Table for D & E**
- Use pivot tables to summarize the sectors (for point 4) and salaries (for point 5). You will pivot on the sector and summarize the job count and average salary.

### Step 3: Create the Pivot Tables

Here’s how you can create the pivot tables for each section:

1. **State with the Most Data Science Jobs**:
   - **Rows**: State
   - **Values**: Count of Jobs (Data Science Jobs)
   - **Chart**: Insert a bar chart for visual clarity.

2. **Job Role with the Highest Average Salary**:
   - **Rows**: Job Role
   - **Values**: Average Salary
   - **Chart**: Insert a column chart to visualize the highest-paying roles.

3. **Company Size with the Highest Salary**:
   - **Rows**: Company Size
   - **Values**: Average Salary
   - **Chart**: Use a column or bar chart to highlight the company size with the highest salary.

4. **Sector with the Most and Least Data Science Jobs**:
   - **Rows**: Sector
   - **Values**: Count of Jobs (Data Science Jobs)
   - **Chart**: Bar or pie chart to show the distribution.

5. **Sector with the Min and Max Average Salary**:
   - **Rows**: Sector
   - **Values**: Average Salary
   - **Chart**: A column chart to show the min and max salary per sector.

### Step 4: Add Slicers for Interactivity
Slicers allow you to filter data dynamically and make your dashboard interactive:
1. Select your pivot table (e.g., Role, Size, State).
2. Go to **Insert** → **Slicer**.
3. Add slicers for **Role Type**, **Size**, and **State**.
4. Ensure that slicers are linked to the relevant pivot tables.

### Step 5: Add a Map (Optional)
If your version of Excel supports maps, you can add a map to visualize data by location:
1. Select your pivot table (e.g., for states).
2. Go to **Insert** → **Map**.
3. Customize the map to show the number of data science jobs or average salaries by state.

### Step 6: Design and Color Settings
Make sure your dashboard is visually appealing:
1. Use consistent colors for different charts (e.g., blue for average salary, green for job counts).
2. Apply conditional formatting for salary data (e.g., higher salaries in green, lower salaries in red).
3. Add a title and make sure the layout is neat and easy to navigate.

### Step 7: Finalize the Dashboard
- Organize all your tables, charts, and slicers neatly on a single sheet.
- Ensure all charts and pivot tables are labeled correctly.
- Test the slicers to make sure they are functioning properly and filtering the data as expected.

### Step 8: Save and Share
Once your dashboard is complete, save the file, and you're ready to share it or present it!

Would you like more specific guidance on creating any of the pivot tables or charts, or help with the design and layout?

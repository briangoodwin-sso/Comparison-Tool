# M27 Symphonic Comparison Tool


A simple tool to explore and analyze Seattle Symphony performance data.


## What Does It Do?


This tool helps you:
- **Filter** performance data by season, production code, quarter, and date ranges
- **Search** for specific titles or program content
- **View statistics** like total ticket revenue, average attendance, and more
- **Download** filtered results as a CSV file for further analysis


## How to Use It


### Getting Started


1. **Open the tool**
   - In your web browser, visit [this link](https://briangoodwin-sso.github.io/Comparison-Tool/).


2. **Load your data**
   - Click the "Choose File" button at the top
   - Select the CSV file you want to analyze (like `MKT_searchable_season.csv`)
   - The tool will display how many rows were loaded


### Filtering Your Data


Use the filter options to narrow down the data you want to see:


- **Season FY** - Select one or more fiscal years (hold Ctrl/Cmd to select multiple)
- **Code** - Filter by production codes (SUB 01, SUB 02, etc.)
- **Quarter** - Filter by quarter (Q1, Q2, Q3, Q4)
- **Search Title (fuzzy)** - Type part of a title to find matches (example: "Mozart")
- **Program contains** - Search within the program details
- **First Perf from/to** - Select date ranges for performance dates


After setting your filters, click the **Apply** button to update the results.


To start over, click **Clear filters**.


### Understanding the Results


**Statistics Cards** (at the top):
- Number of rows that match your filters
- Total ticket revenue for all matching performances
- Total number of performances
- Average revenue per performance
- Average paid tickets per performance
- Average comp tickets per performance


**Data Table** (below):
- Shows all performances that match your filters
- Matched terms are highlighted in yellow
- Scroll to see all columns and rows


### Downloading Results


Click the **Download matches CSV** button to save the filtered data as a CSV file. This file can be opened in Excel, Google Sheets, or any spreadsheet program.


## Tips


- **Multiple selections**: Hold Ctrl (Windows) or Cmd (Mac) while clicking to select multiple options in dropdown lists
- **Clear text searches**: Leave search boxes empty to see all results
- **Date ranges**: You can set just a "from" date, just a "to" date, or both
- **Yellow highlights**: Any data that matches your active filters will be highlighted in the table


## Technical Requirements


- Any modern web browser (Chrome, Firefox, Safari, or Edge)
- No internet connection required - everything runs locally on your computer
- Your CSV file should include these columns:
  - season_fy, code, search_title, composer, search_text, first_perf_date
  - search_string_2, num_perfs, ticket_revenue, paid_ticket_count, comp_ticket_count, quarter


## Need Help?


If something isn't working:
1. Make sure your CSV file has all the required columns
2. Try refreshing your browser and loading the file again
3. Check that your browser is up to date


---


*This tool analyzes performance data locally in your browser. No data is sent to external servers.*

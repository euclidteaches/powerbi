# Get started with Power BI (lab)
![](https://agilethought.com/wp-content/uploads/2018/10/power-BI-768x432.png)
## Goal
* Get a feel for Power BI Desktop

## Setup
* Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop)

## Steps
### Connect to Retirement data
1. Connect to the sample retirement data. ([URL](https://www.bankrate.com/retirement/best-and-worst-states-for-retirement/))
2. Remove bad rows and rename columns
3. Change the number columns to the Whole Number data type.
4. Sort by Overall Rank, then Sort by Weather ascending, Remove 10 Bottom Rows.
5. Remove *Crime, Culture, and Wellness* columns
6. Rename table title to "Best states for sunglass sales"

### Connect to State data
1. Connect to sample state abbreviations. ([URL](https://en.wikipedia.org/wiki/List_of_U.S._state_abbreviations))
2. Remove all columns except:
   * Name and status of region
   * Name and status of region2
   * ANSI
3. Filter *Name and status of region2* column by *State*
4. Rename columns
5. Rename table to State codes

### Merge Queries
1. Select Merge Queries option
2. Choose State columns
3. Expand to include Abbreviation column

### Build Reports
#### Map View
1. Add State column
2. Add Filter for Top 10 by weather
3. Rename Visual Title

#### Bar Chart
1. Add State and Weather column
2. Sort Ascending
3. Add Filter for Top 10 by weather

### Style the Report
1. Add several additional visuals
2. Add a background image
3. Add a title

## Resources
* Sample Retirement Data Table ([URL](https://www.bankrate.com/retirement/best-and-worst-states-for-retirement/))
* State Abbreviations ([URL](https://en.wikipedia.org/wiki/List_of_U.S._state_abbreviations))
* [Step-by-step Instructions](https://docs.microsoft.com/en-us/power-bi/fundamentals/desktop-getting-started)
* [Shape and combine data](https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-shape-and-combine-data)
* [Connect to data](https://docs.microsoft.com/en-us/power-bi/connect-data/desktop-connect-to-data)
* [Report View](https://docs.microsoft.com/en-us/power-bi/create-reports/desktop-report-view)
* [Share a dashboard](https://docs.microsoft.com/en-us/power-bi/collaborate-share/service-share-dashboards)
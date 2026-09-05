# Search Trends Analysis
This project analyzes search trend data across different locations, years, categories, rankings, and search queries.
The original dataset is stored as `trends.csv`, while the cleaned and transformed version is stored as `trends_cleaned.csv`.

### Main fields
- **Location**: geographic location associated with the search
- **Year**: year of the search trend record
- **Category**: category of the search query
- **Rank**: search ranking position (1–5)
- **Query**: search term or query

## ETL and Data Cleaning

The dataset was prepared through the following steps:
1. **Missing values** were checked and handled where required.
2. **Duplicate records** were identified and removed during the data-cleaning stage.
3. **Data types** were standardized, with Year and Rank stored as numerical values and categorical fields stored as text.
4. **Column names** were standardized for consistency and readability.
5. **Text values** were cleaned by removing unnecessary spaces and inconsistencies.
6. **Data validation** was performed to check for errors and ensure valid Year and Rank values.
7. The cleaned dataset was then exported as `trends_cleaned.csv`.

## Dashboard
`trends.pbix` contains the Power BI dashboard created from the cleaned dataset.

The dashboard visualizes:
- Total searches
- Unique search queries
- Rank #1 searches
- Search activity over time
- Top search categories
- Most frequent search queries
- Search ranking distribution

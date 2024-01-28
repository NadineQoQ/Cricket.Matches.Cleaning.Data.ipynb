# Cricket.Matches.Cleaning.Data.ipynb
🏏 This Python script focuses on cleaning and analyzing cricket player statistics from a CSV file. The analysis involves data cleaning operations, handling missing values, transforming columns, and extracting valuable insights.

## Features

### Data Cleaning
- Renaming columns for better clarity.
- Handling null values by replacing them with zeros.
- Removing duplicates from the dataset.
- Splitting and transforming columns like 'Span' into 'Start_date' and 'End_date'.
- Extracting country information from the 'Player' column.

### Statistical Analysis
- Computing the average career length of players.
- Calculating the average batting strike rate for players with a career length greater than 10 years.
- Determining the number of players who played before 1990.

### Additional Insights
- Finding the maximum value of 'Highest_inns_score' by country.

## Usage

1. **Load Dataset:**
   - Load your cricket matches dataset (CSV file) into the script.

2. **Run the Script:**
   - Execute the Python script to perform data cleaning and statistical analysis.

3. **Explore Insights:**
   - Review the calculated metrics and insights derived from the cricket stats.

Feel free to customize and adapt the script to your dataset or cricket statistics of interest.

## Getting Started

```bash
# Install required library
pip install pandas

## Happy coding! 🚀

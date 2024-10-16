# Demographic Data Analyzer

This project analyzes demographic data from a CSV dataset to extract meaningful insights about education, salary, work hours, and other demographic factors.

## Project Description

This data analyzer performs various statistical analyses on adult demographic data to answer specific questions about education levels, income brackets, working hours, and geographical distribution of high-income earners.

## Data Source

The project uses a dataset named `adult.data.csv` which contains demographic information including:
- Age
- Education level
- Race
- Sex
- Working hours
- Native country
- Salary brackets
- Occupation

## Key Analyses

The analyzer performs the following key analyses:

1. **Race Distribution**
   - Counts the representation of each race in the dataset

2. **Gender Analysis**
   - Calculates the average age of men in the dataset

3. **Education Statistics**
   - Calculates the percentage of people with Bachelor's degrees
   - Analyzes income levels (>50K) for people with advanced degrees (Bachelors, Masters, or Doctorate)
   - Compares income levels of people with and without advanced education

4. **Work Hours Analysis**
   - Identifies the minimum working hours per week
   - Analyzes the percentage of high earners (>50K) among minimum-hour workers

5. **Geographical Analysis**
   - Determines the country with the highest percentage of high-income earners (>50K)
   - Calculates the percentage of high earners in each country

6. **Specialized Analysis**
   - Identifies the most popular occupation among high earners in India

## Dependencies

- Python 3.x
- pandas
- numpy

## Usage

1. Ensure you have the required dependencies installed:
```bash
pip install pandas numpy
```

2. Place your `adult.data.csv` file in the same directory as the script

3. Run the script:
```bash
python demographic_data_analyzer.py
```

## Output Format

The script prints various statistics to the console, including:
- Race distribution counts
- Average age of men
- Education level percentages
- Income bracket analyses
- Working hour statistics
- Geographical income distribution
- Occupation analysis for specific countries

## Data Privacy Note

Ensure you have the necessary permissions to use the demographic dataset and handle the data in accordance with relevant privacy regulations.

## Contributing

Feel free to fork this project and submit pull requests with improvements or additional analyses.

## Author

Abrefah, M J

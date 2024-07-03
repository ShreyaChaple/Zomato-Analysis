
# Zomato Data Analysis

This project involves analyzing a dataset from Zomato to gain insights into restaurant ratings, types, and other attributes. The analysis includes data cleaning, transformation, and visualization to provide a comprehensive understanding of the dataset.

## Download Dataset
https://drive.google.com/file/d/1FyBmcd2gMub4PmlMcG0qlTSrMaSbntAF/view?usp=sharing

## Table of Contents
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Author](#author)
- [License](#license)

## Dataset
The dataset used in this project is a CSV file containing information about various restaurants listed on Zomato. The dataset includes columns such as:
- `name`: Name of the restaurant
- `online_order`: Whether the restaurant accepts online orders
- `book_table`: Whether the restaurant accepts table bookings
- `rate`: Rating of the restaurant
- `votes`: Number of votes
- `location`: Location of the restaurant
- `rest_type`: Type of restaurant
- `cuisines`: Cuisines served
- `approx_cost(for two people)`: Approximate cost for two people
- `reviews_list`: List of reviews

## Data Cleaning
1. **Missing Values:**
   - Identified columns with missing values and calculated the percentage of missing values for each column.
   - Dropped rows with missing ratings (`rate` column).

2. **Data Transformation:**
   - Split the `rate` column to extract numeric values and replace 'NEW' and '-' with 0.
   - Converted the `rate` column to a float type.
   - Cleaned the `approx_cost(for two people)` column to remove non-numeric characters and converted it to a float type.

## Data Analysis
1. **Average Rating:**
   - Calculated the average rating for each restaurant and sorted them in descending order.

2. **Distribution of Ratings:**
   - Analyzed the distribution of ratings to check for normality using the Shapiro-Wilk test.

3. **Restaurant Chains:**
   - Identified the top restaurant chains based on the number of outlets.

4. **Online Orders and Table Bookings:**
   - Analyzed the proportion of restaurants accepting online orders and table bookings.

5. **Restaurant Types:**
   - Identified the most common types of restaurants.

6. **Votes Analysis:**
   - Analyzed the distribution of votes to identify the most popular restaurants based on the number of votes.

7. **Highly Rated Restaurants:**
   - Identified the highly rated restaurants based on the number of votes.

8. **Worst Restaurants:**
   - Identified the worst restaurants based on ratings and the number of votes.

9. **Location Analysis:**
   - Analyzed the distribution of restaurants across different locations.

10. **Cuisines Analysis:**
    - Identified the top 10 cuisines served by the restaurants.

11. **Cost Analysis:**
    - Analyzed the distribution of the approximate cost for two people.

## Visualizations
1. **Bar Plot of Average Ratings:**
   - Visualized the top 15 restaurants based on average ratings.

2. **Distribution Plot of Ratings:**
   - Visualized the distribution of restaurant ratings.

3. **Bar Plot of Top Restaurant Chains:**
   - Visualized the top 15 restaurant chains.

4. **Pie Charts for Online Orders and Table Bookings:**
   - Visualized the proportion of restaurants accepting online orders and table bookings.

5. **Bar Plot of Restaurant Types:**
   - Visualized the distribution of the top 15 restaurant types.

6. **Bar Plot of Highly Rated Restaurants:**
   - Visualized the highly rated restaurants based on the number of votes.

7. **Bar Plot of Worst Restaurants:**
   - Visualized the worst restaurants based on ratings and the number of votes.

8. **Count Plot of Restaurant Locations:**
   - Visualized the distribution of restaurants across different locations.

9. **Bar Plot of Top Cuisines:**
   - Visualized the top 10 cuisines served by the restaurants.

## Conclusion
The analysis provided valuable insights into the restaurant landscape on Zomato, highlighting the most popular restaurant chains, types, and cuisines. It also identified the highly rated and worst-rated restaurants based on customer feedback. These insights can be useful for restaurant owners, customers, and Zomato for improving their services and offerings.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scipy

## Usage
1. Ensure you have the necessary libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
2. Load the dataset and run the analysis using the provided code snippets.

## Author
[Your Name]

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

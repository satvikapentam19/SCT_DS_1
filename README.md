# SCT_DS_1
Create a bar chart or histogram to visualize the distribution of a categorical variable,such as the distribution of ages or genders in a population.
# --------------------------------------------
# DESCRIPTION: BAR CHART & HISTOGRAM CREATION
# --------------------------------------------

# 1. Import Tools
#    - Use pandas for handling data
#    - Use matplotlib for creating visualizations

# 2. Load or Create Data
#    - Prepare a dataset containing:
#        a) Categorical variable (e.g., Gender)
#        b) Numerical variable (e.g., Age)

# 3. Identify Variable Type
#    - If variable is categorical → use Bar Chart
#    - If variable is numerical → use Histogram

# 4. Prepare Data
#    - Clean and organize your data
#    - For categorical data: count the frequency of each category
#    - For numerical data: decide on number of bins (intervals)

# 5. Create Bar Chart (Categorical Variable)
#    - X-axis: categories (e.g., Male, Female, Other)
#    - Y-axis: frequency/count of each category
#    - Each bar’s height shows how often that category appears
#    - Use plt.bar() or df['Column'].value_counts().plot(kind='bar')

# 6. Create Histogram (Numerical Variable)
#    - X-axis: intervals (bins) of numeric data
#    - Y-axis: number of observations within each interval
#    - Each bar covers a range of values
#    - Use plt.hist() to create the histogram

# 7. Customize Charts
#    - Add a title, axis labels, and colors for clarity
#    - Example:
#         plt.title('Distribution of Gender')
#         plt.xlabel('Gender')
#         plt.ylabel('Number of People')

# 8. Interpret the Charts
#    - Bar Chart: Identifies the most or least common category
#    - Histogram: Shows how values are spread or grouped
#    - Look for trends, peaks, or skewed distributions

# 9. Summary
#    - Bar Chart → Best for categorical variables
#    - Histogram → Best for numerical variables
#    - Both visualize data distribution effectively

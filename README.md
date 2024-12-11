# Hypothesis-Testing
# Title: Hypothesis Testing with Python on Website A/B Testing
This project uses Python to perform hypothesis testing on A/B test data, comparing two website themes (Light and Dark). It analyzes metrics like Click Through Rate, Conversion Rate, Bounce Rate, and Scroll Depth to determine statistically significant differences, providing insights into theme performance.

## **Introduction**
This project demonstrates the use of hypothesis testing to analyze the performance of two website themes—Light Theme and Dark Theme—using Python. The aim is to determine which theme performs better across several metrics, including:
- Click Through Rate (CTR)
- Conversion Rate
- Bounce Rate
- Scroll Depth

Hypothesis testing is a powerful tool for making data-driven decisions, and this project serves as a practical example for applying statistical techniques in real-world scenarios.

## **Features**
- Exploratory Data Analysis (EDA)
- Two-sample t-tests to compare metrics between the themes
- Statistical significance determination based on p-values
- Detailed interpretation of results for each metric

## **Dataset**
The dataset includes 1,000 records with the following columns:
- `Theme`: Light Theme or Dark Theme
- `Click Through Rate`
- `Conversion Rate`
- `Bounce Rate`
- `Scroll_Depth`
- Additional demographic and session-related attributes

## **Project Workflow**
1. **Data Exploration**: Summary statistics and missing value checks.
2. **Metric Comparison**: Grouping and analyzing averages for each theme.
3. **Hypothesis Testing**: Two-sample t-tests performed for:
   - Click Through Rate
   - Conversion Rate
   - Bounce Rate
   - Scroll Depth
4. **Interpretation of Results**: Statistical significance determined for each metric.

## **Results Summary**
| Metric                | T-Statistic | P-Value | Result                            |
|-----------------------|-------------|---------|-----------------------------------|
| Click Through Rate    | -1.978      | 0.048   | Statistically Significant         |
| Conversion Rate       | 0.475       | 0.635   | Not Statistically Significant     |
| Bounce Rate           | -1.207      | 0.230   | Not Statistically Significant     |
| Scroll Depth          | 0.755       | 0.450   | Not Statistically Significant     |

### **Key Findings**
- **Click Through Rate**: Dark Theme performs slightly better (statistically significant).
- **Conversion Rate, Bounce Rate, Scroll Depth**: No significant differences observed.

## **Technologies Used**
- **Python**: pandas, scipy.stats  
- **Libraries**:  
  - pandas for data manipulation  
  - scipy.stats for statistical tests  

## **How to Run**
1. Clone this repository:  
   git clone https://github.com/IshikaRastogi/Hypothesis-Testing.git
   cd Hypothesis-Testing
2. Install the required libraries:
   pip install pandas scipy
3. Open the Jupyter Notebook:
   jupyter notebook hypothesis_testing_ab_test.ipynb







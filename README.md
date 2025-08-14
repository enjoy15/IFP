# Online Retail Transaction Analysis

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content
The "Online Retail Transaction" dataset contains information on transactions made by customers through an online retail platform. The dataset includes data on the products that were purchased, the quantity of each product, the date and time of each transaction, the price of each product, the unique identifier for each customer who made a purchase, and the country where each customer is located. This dataset can be used to analyze customer behavior and preferences, identify popular products, and optimize pricing and marketing strategies. The dataset is well-suited for data analysis and machine learning applications, as it contains a large volume of transactional data that can be used to train predictive models and make data-driven decisions.

### Column Descriptors
- InvoiceNo: Unique identifier for each transaction
- StockCode: A code used to identify the product that was purchased
- Description: A brief description of the product that was purchased
- Quantity: The quantity of the product that was purchased
- InvoiceDate: The date and time that the purchase was made
- UnitPrice: The price of one unit of the product that was purchased
- CustomerID: The unique identifier for the customer who made the purchase
- Country: The country where the customer who made the purchase is located

## Business Requirements

Analyse online retail transaction data to understand customer behaviour, identify popular products, and optimise pricing and marketing strategies. Provide insights into customer behaviour, popular products, and pricing strategies to improve sales and marketing efforts.

## Hypothesis and how to validate?
### Hypotheses:
1. **H1**: The UK market generates the majority of revenue due to being the primary market
   - **Validation**: Analyse revenue by country and plot top 10 countries by revenue

2. **H2**: Higher-priced items have lower quantities sold (inverse relationship)
   - **Validation**: Plot unit price vs quantity to see relationship 

3. **H3**: Customer segments can be effectively identified using RFM analysis
   - **Validation**: RFM segmentation and validation through business metrics
  
## Project Plan

### High-Level Analysis Steps:

1. **Data Extraction**: Load raw transaction data from CSV format
2. **Data Cleaning**: Handle missing values, remove duplicates, filter invalid transactions
3. **Feature Engineering**: Create derived metrics (total value, time-based features, customer metrics)
4. **Exploratory Data Analysis**: Statistical summaries and initial insights
5. **Customer Segmentation**: RFM analysis and customer classification
6. **Visualization**: Create comprehensive charts
7. **Business Intelligence**: Generate actionable insights and recommendations

### Data Management Approach:
- **Collection**: Structured CSV data with transactional records
- **Processing**: Python-based ETL pipeline with pandas for data manipulation
- **Analysis**: Statistical analysis using numpy, descriptive analytics, and segmentation
- **Interpretation**: Business-focused insights with clear recommendations

### Research Methodology:
- **Descriptive Analytics**: Summarizing and describing the main features of a dataset
- **Segmentation Analysis**: RFM methodology for customer classification
- **Time Series Analysis**: Trend identification and seasonality detection

## The rationale to map the business requirements to the Data Visualisations
1. **Customer Behavior Analysis**: Understand purchasing patterns and frequency
2. **Product Performance**: Identify best-selling products and revenue drivers
3. **Market Segmentation**: Segment customers based on RFM (Recency, Frequency, Monetary) analysis
4. **Marketing Optimization**: Determine optimal timing and targeting for marketing campaigns
5. **Geographic Analysis**: Understand market performance across different countries
6. **Revenue Growth**: Provide actionable insights to increase sales and customer retention

## Analysis Techniques Used

### Data Analysis Methods:
1. **Descriptive Statistics**: Mean, median, standard deviation for understanding data distribution
2. **RFM Analysis**: Customer segmentation based on Recency, Frequency, and Monetary value
3. **Time Series Analysis**: Trend identification and seasonal pattern detection
4. **Correlation Analysis**: Relationship identification between variables
5. **Distribution Analysis**: Understanding data spread and outlier identification

### Data Structure Approach:
- **Pandas DataFrame**: Primary data structure for manipulation and analysis
- **Groupby Operations**: Aggregation for customer and product-level insights
- **Descriptive Statistics**: Basic statistics

### Limitations and Alternatives:
- **Time Period**: Limited to available date range; longer historical data would improve trend analysis
- **External Factors**: No external economic or seasonal factors considered; could be enhanced with external data sources
- **Predictive Modeling**: Current analysis is descriptive; could be extended with machine learning for forecasting

### Generative AI Usage:
- **Code Optimization**: Used AI assistance for efficient pandas operations and visualization improvements
- **Documentation**: AI-assisted documentation generation and README structuring
- **Best Practices**: AI guidance on data analysis methodologies and statistical approaches
- **Visualization Enhancement**: AI suggestions for effective chart types and styling

## Ethical considerations

### Data Privacy:
- **Customer Anonymization**: Customer IDs are anonymised identifiers, no personal information exposed
- **Data Aggregation**: Analysis performed at aggregate levels to protect individual privacy
- 
### Bias and Fairness:
- **Geographic Bias**: UK-heavy dataset may not represent global patterns; acknowledged in limitations
- **Temporal Bias**: Single-year data may not capture long-term trends; noted for future improvements
- **Selection Bias**: Online-only transactions may not represent full retail landscape
- 
## Unfixed Bugs
### Knowledge Gaps
- **Advanced Statistical Testing**: Implemented correlation analysis and distribution testing
- **Business Intelligence**: Enhanced understanding of retail KPIs and customer metrics
- **Data Visualization Best Practices**: Improved chart selection and styling for business audiences

## Development Roadmap

### Challenges Overcome:
* Handling large dataset using ETL pipeline and pandas operations
* Create complex visualizations using Matplotlib / Seaborn / Plotly

### Future Learning Goals:
* Learn interactive dashboard creation
* Develop statistical testing for marketing campaign effectiveness

## Main Data Analysis Libraries
* Pandas: For data cleaning and manipulation. 
* NumPy: For numerical computations. 
* Matplotlib / Seaborn / Plotly: For visualizations.

## Kanban
[Project Planning] (https://github.com/users/enjoy15/projects/1)

## Data source 
[Kaggle] (https://www.kaggle.com/datasets/abhishekrp1517/online-retail-transactions-dataset )

## Acknowledgements
Thanks Vasi for the support


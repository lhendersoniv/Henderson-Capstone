SpaceX Falcon 9 Landing Prediction Capstone
Max Henderson



PROJECT OVERVIEW

This project analyzes historical SpaceX Falcon 9 launch data to understand and predict first-stage landing success.

The ability to accurately predict landing outcomes is critical because first-stage recovery significantly reduces launch costs and provides SpaceX with a competitive advantage over traditional launch providers.

This end-to-end data science project includes:

- Data collection via REST API

- Web scraping

- Data wrangling and feature engineering

- Exploratory Data Analysis (EDA)

- SQL-based analysis

- Geospatial visualization

- Interactive dashboard development

- Predictive modeling using classification algorithms



BUSINESS PROBLEM

Reusable rocket technology reduces launch costs substantially compared to expendable launch systems. Predicting first-stage landing success enables:

- Estimation of cost savings

- Assessment of operational reliability

- Risk evaluation based on mission parameters

- Competitive benchmarking within the aerospace launch industry



DATA SOURCES AND FEATURES

Data was collected from:

- SpaceX REST API

- Wikipedia (via web scraping)

- Structured SQL dataset for querying



The dataset includes:

- Launch site

- Payload mass

- Orbit type

- Booster version

- Reuse count

- Landing outcome

- Geographic coordinates

- Flight number

- Mission date

Target Variable:

Class
- 1 = Successful landing
- 0 = Unsuccessful landing



EXPLORATORY DATA ANALYSIS

Key findings:

- Landing success improved dramatically after 2014.

- Geostationary Transfer Orbit (GTO) missions show lower landing success compared to Low Earth Orbit (LEO) and ISS missions.

- Heavier payloads correlate with increased probability of landing failure.

- Newer booster versions (e.g., Block 5) demonstrate significantly higher success rates.

- Launch site influences landing success probability.



EDA techniques used:

- Scatter plots

- Line charts

- Bar charts

- Correlation analysis

- SQL aggregations

- Time series trend analysis



GEOSPATIAL ANALYSIS

An interactive map was created to visualize:

- Launch site locations

- Landing outcomes by site

- Geographic distribution patterns




INTERACTIVE DASHBOARD

A dynamic dashboard was built to allow users to:

- Filter launches by site

- Adjust payload mass range

- View success distribution

- Explore payload versus landing outcome



PREDICTIVE MODELING

Classification models developed and evaluated:

- Logistic Regression

- Support Vector Machine

- K-Nearest Neighbors

- Decision Tree Classifier

Model development process:

- Feature encoding (one-hot encoding)

- Standardization of numerical variables

- Train-test split

- Hyperparameter tuning using grid search

- Model evaluation using accuracy and confusion matrix

Best performing model:
- The tuned Decision Tree model achieved approximately 80 to 85 percent accuracy depending on train-test split.

Important predictive features:

- Payload mass

- Orbit type

- Launch site

- Booster reuse characteristics

- Flight number



Conclusion: Landing outcomes are predictable using mission metadata and engineering characteristics.

TECHNOLOGIES USED

- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

- Plotly

- Dash

- Folium

- SQLite / SQL

- Scikit-learn

- BeautifulSoup

KEY TAKEAWAYS

- SpaceX landing success rates improved significantly over time.

- Booster evolution and reusability contribute strongly to reliability.

- Mission profile (payload mass and orbit) materially affects recovery probability.

- Machine learning models can meaningfully predict landing outcomes.

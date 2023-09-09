# **CUSTOMER CHUN ANALYSIS**

![green-divider](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)
<p>
This project worked on is a real world dataset from a telecom company that includes customer information, such as demographics, usage patterns, and whether they churned (i.e., left the company) or not. The analysis comprises of steps i.e cleaning and preprocessing, exploration, modelling, visualisation and summary.
<br>
The analysis was carried out with objectives stated as follows:
<ol>
    <li>Cleaning and Preprocessing the dataset.</li>
    <li>Exploratory Data Analysis.</li>
    <li>Convey information through Data Visualisation that affects customer churn.</li>
    <br>
    <ol>
        <li><b>Cleaning and Preprocessing the dataset:</b>
        <p>This process is tantamount and a prereauisite to other steps of Data Analysis. It entails viewing the properties, size, statistical summary and size of the data. Major aim of this process includes:
        <ul style= 'list-style-type:square'>
        <li>Removing Duplicates: duplicated values will skew analysis performance, to avoid that, it's always best to check for duplicates using variable<code>.duplicated().sum()</code>(to check for the count of duplicated values) and drop them.</li>
        <li>Treating Missing Values: pinpoint missing values, then its either to drop the rows affected or use the <code>fillna</code> method, with the use of mean and median to fill missing values.</li>
        <li>Converting Data types: data types that do not conform with the pattern of the feature e.g a date in string format, or an integer in a string format, should be converted to the right data type.</li>
        <li>Detecting Outliers: outliers can be detected through the use of quartile range boundaries, box plot and scatter plot. It affects the mean of the dataset, which in turn affects the standard deviation.</li>
        <li>Analysis of Qualitative Datasets: categorical data can be encoded through <code>OneHotEncoder</code>, <code>LabelEncoder</code>, which are <code>scikit-learn</code> algorithms and can also be performed with <code>pandas</code> <code>get_dummies</code> function.</li>
        </ul>
        </p>
        </li>
        <br>
        <li><b>Exploratory Data Analysis:</b>
        <p>This helps explore the questions to ask, and involves scanning through the data for quantitative and qualitative features.
        <ul style= 'list-style-type:square'>
        <li>Perform Descriptive Statistics: calculating the statistical summary for quantitative/numerical features with the <code>describe</code> function, which displays the count, mean, std, min, 1st quantile,median, 3rd quantile, maximum values of wach numerical feature.</li>
        <li>Analyse the distribution of categorical features: distribution includes counts, ratios.</li>
        <li>Correlation: identify the relationship of numerical features through heatmaps and scatter plots.</li>
        <li>Hypothesis Testing: with the use of t-test to help make inferences about the data and gain insights from the result.</li>
        </ul>
        </p>
        </li>
        <br>
        <li><b>Convey information through Data Visualisation:</b>
        <p>Showcasing the pictorial result of the cleaned and analysed dataset. It comprises of:
        <ul style= 'list-style-type:square'>
        <li>Identifying Trends: this is done through visualisation of scatter plots, line plots and bar plots</li>
        <li>Spread of Categorical and Numerical values: with the use of bar plot, histogram to validate the distribution of the values.</li>
        <li>Distribution of Numeric values: the use of scatter plots, histogram, and density plots.</li>
        </ul>
        </p>
        </li>
    </ol>
</ol>
<br>
<p>The following visualisation libraries were used:
<ul style='list-style-type:disc'>
    <li><code>matplotlib</code></li>
    <li><code>seaborn</code></li>
    <li><code>plotly</code></li>
</ul>
</p>

![Churned_Customers](https://github.com/aiyegboka/Telcom/assets/40834421/c4758d40-addd-40ee-b9c0-82ab397a9c99)

![Internet Service Distribution](https://github.com/aiyegboka/Telcom/assets/40834421/878e4c26-d7eb-4fa2-b787-e01b83702c17)

</p>

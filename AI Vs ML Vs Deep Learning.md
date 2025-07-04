==**Artificial Intelligence**==: The broadest, encompassing any technique that enables computers to mimic human intelligence. This includes areas like problem-solving, reasoning, learning & perception.

**==Machine Learning==**: A subset of AI that focuses on algorithms that can learn from and make predictions or decisions based on data, without being explicitly programmed for the task.

**==Deep Learning==**: A specialized subset of M that utilizes artificial neural networks with multiple layers (hence 'deep) to analyze and learn complex patterns in data.

# Types of Data in ML
==Data is the lifebblood of machine learning. Algorithms learn patterns and make predictions based on the data they are trained on.==

*==Structured Data==*
Data organized in a predefined format, typically with rows and columns, making it easy to store, access, and analyze.
*Characteristics*
	* Well-defined schema or structure (e.g., tables with columns and rows).
	* Easily searchable and queryable using SQL or other query languages.
	* Suitable for traditional database systems and data warehousing.*
*Examples*
* Relational databases (MYSQL, PostgreSQL, Oracle)
* CSV files
* Excel spreadsheets
* Tabular data in pandas DataFrames(Python).
*
==*Unstructured Data==*
Data that does not conform to a predefined format or schema, making it challenging to organize and analyze using traditional methods.
*Characteristics*
	* Lacks clear structure or organization.
	* Requires specialized techniques for processing & analysis (e.g. natural language processing, computer vision)
	* Represents a significant portion of the data generated today.*
*Examples*
* Text documents(emails, articles, social media posts)
* Images (photos, medical scans)
* Audio files (music, podcasts, voice recordings)
* Video files (movies, surveillance footage)*

*==Semi-Structured Data==*
Data that has some organizational properties but does not conform to the rigid structure of relational databases. 
*Characteristics*
* Contains tags, markers, or other elements that provide some structure.
* Easier to parse and analyze than completely unstructured data.
* Often used for data exchange and web applications.*
*Examples*
* JSON
* XML
* HTML
*==Time Series Data*==
A sequence of data points collected at successive points in time.
*Characteristics*
* Data points are ordered chronologically
* Used for forecasting trend analysis & anomaly detection.
* Often exhibit patterns like seasonality & trends.
*Examples*
* Stock Prices
* Weather data
* Sensor readings
* website traffic*

 *==Categorical Data==*
 Data that represents categories or groups, rather than numerical values.
 **==Types==**
 *Nominal*: Categories with no inherent order (e.g., colors ,types of fruit, countries)
 *Ordinal*: Categories with a meaningful order or ranking (e.g., education levels(high school, bachelor's, master's), customer satisfaction ratings (low, medium, high)).

*==Numerical Data==*
Data that represents numerical measurements or counts.
**==Types==**
*Discrete*: Data that can only take on specific, separate values (e.g., no. of children, no. of cars) Typically integers.
*Continuous*: Data that can take on any value within a given range (e.g., height, weight, temperature.)
*Example*
Discrete : 0,1,2
Continuous: 1.1, 3.3
# data-analysis-project
SQL analysis and data visualization of a netflix shows dataset

Difficulties Faced During the Import Process
1.File Format and Structure: The dataset came in a CSV format, which initially seemed straightforward to import. However, issues arose due to inconsistent delimiters and quotation marks within the dataset. Some fields contained commas and quotes, which caused errors during import into MySQL Workbench.

2.Data Types: Choosing the correct data types for each column was challenging. For example, the release_year column needed to be an integer, while columns containing text descriptions required careful handling to avoid truncation or loss of data.

3.Handling Null Values: The dataset had several null values, especially in columns like director and cast. Ensuring that these null values were correctly handled and did not disrupt SQL queries required additional attention.

4.Data Size and Performance: The dataset was relatively large, leading to performance issues during import and while running queries. Indexing the appropriate columns was necessary to improve query performance.

Interesting Insight from the Dataset
One particularly interesting insight from the Netflix dataset is the distribution of content types over the years. By examining the data, it became apparent that the number of TV Shows added to Netflix has significantly increased over the past few years compared to movies. This trend highlights Netflix's strategic shift towards producing and acquiring more TV series content, possibly to engage viewers with ongoing subscriptions rather than one-time movie views.

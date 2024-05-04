# AI Career Impact Analysis with PCA

This project focuses on analyzing responses from a Google Form survey designed to understand public perceptions of artificial intelligence (AI), specifically how it affects careers, job security, and future work trends. The collected data will be analyzed using Principal Component Analysis (PCA) and clustering techniques to identify patterns and classify users. An SQL database is used to store and manage the survey data.

## Project Overview

The main goal of this project is to classify users based on their perceptions of AI's impact on careers and jobs. The data comes from a Google Form survey with questions about work environment preferences, employment types, attitudes toward AI, career goals, and more. The project uses PCA to reduce data dimensionality and clustering to classify users into distinct groups.

## Designing the Google Form

The Google Form used in this project was crafted to gather unique information about each respondent, focusing on their demographics, career aspirations, and attitudes toward AI. This structure allows for effective classification in a database and helps identify patterns through PCA and clustering.

### Survey Structure and Purpose

The Google Form consists of several sections, each designed to capture specific information:

- **Demographic Information**: Questions about age, gender, education, region, and major help categorize respondents into basic groups for further analysis.

- **Career Aspirations and Preferences**: This section collects data on preferred work environments, employment types, and interest in starting a business. These questions help identify unique career-related attributes for each respondent.

- **AI Knowledge and Perceptions**: Questions about knowledge of AI, its impact on jobs, and attitudes toward AI are key to understanding how respondents view AI's role in their careers and society.

- **Job Security and Adaptability**: This section focuses on how respondents perceive the potential risks and benefits of AI in the workplace, including concerns about automation and their readiness to adapt to AI-driven changes.

### Unique Information for Classification

The Google Form was designed to capture unique combinations of responses, allowing for effective classification in the database. Here are some examples of how the questions contribute to unique user profiles:

- **Demographics**: By collecting age, gender, education level, and region, the survey creates a baseline for clustering users into broad demographic groups.

- **Career Preferences**: Questions about remote work, employment type, and interest in entrepreneurship allow for classification based on career aspirations and work environments.

- **Attitudes Toward AI**: Capturing a range of attitudes towards AI—from enthusiastic to cautious—provides a way to classify users based on their perception of AI's impact on their future careers.

- **Job Security and Adaptability**: Questions about job security and readiness to adapt to AI create an additional layer of classification, highlighting groups with similar concerns or optimism about AI in the workplace.

By collecting this unique information, the Google Form provides a comprehensive dataset that can be analyzed through PCA to reduce dimensionality and clustered to identify distinct groups based on their responses.

## Understanding PCA

Principal Component Analysis (PCA) is a statistical technique used to reduce the dimensionality of a dataset while preserving as much variance as possible. By identifying key components (or principal components), PCA helps simplify complex datasets, making it easier to visualize and analyze underlying patterns.

In this project, PCA is used to:
- Reduce the number of variables from the survey data, focusing on the most significant ones.
- Identify key factors that contribute to how people view AI and its impact on careers.
- Facilitate clustering and other analyses by transforming high-dimensional data into lower-dimensional representations.

## Clustering and User Classification

After applying PCA, clustering techniques are used to classify users based on their survey responses. Clustering involves grouping similar responses together, allowing us to identify patterns and categorize users with similar perspectives on AI and career trends. Techniques such as K-means clustering or hierarchical clustering may be used to achieve this.

## SQL Database for Data Storage

An SQL database is used to store the survey data. SQL (Structured Query Language) is a standard language for managing and querying relational databases. By storing data in an SQL database, you can:
- Efficiently manage large datasets.
- Perform complex queries to retrieve specific subsets of the data.
- Integrate with other data analysis tools and libraries.

In this project, the SQL database is used to:
- Store survey responses in a structured format.
- Fetch data for PCA analysis and clustering.
- Retrieve specific information for additional analysis and reporting.


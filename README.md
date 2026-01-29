# DATA-PIPELINE-DEVELOPMENT

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: Prem Dilip DhumaL

*INTERN ID*: CTIS1752

*DOMAIN*: Data Science

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

#In this task, I created an ETL (Extract, Transform, Load) pipeline using Python. The purpose of this task was to understand how raw data can be automatically processed and prepared before it is used for analysis or machine learning. In real-life applications, data is often incomplete, unstructured, and contains missing or incorrect values. Because of this, preprocessing and transformation are very important steps before using the data.

For developing this project, I used Visual Studio Code (VS Code) as the coding environment. VS Code provided an easy interface to write Python code, manage files, and run programs using the terminal. It also helped in organizing the dataset, script file, and output files in one folder.

The main programming language used was Python, as it is one of the most popular languages for data-related tasks. To build the ETL pipeline, several Python libraries were used. Pandas was used for reading CSV files and handling tabular data. NumPy was used for numerical operations and array handling. Scikit-learn was used for data preprocessing, feature transformation, and pipeline creation.

The ETL process was divided into three main stages.

The first stage was the Extract phase. In this step, raw data was loaded from a CSV file using Pandas. The dataset contained both numerical and categorical columns along with missing values. After loading the data, it was stored in a DataFrame so that further processing could be applied easily. This step represents how data is collected from external sources such as files or databases.

The second stage was the Transform phase, which is the most important part of the pipeline. In this phase, data cleaning and preprocessing were performed. Missing numerical values were handled using mean imputation, while missing categorical values were filled using the most frequent value. Numerical features were standardized using StandardScaler so that all values remain on the same scale. Categorical variables were converted into numerical form using OneHotEncoder.

To make the transformation process efficient and reusable, Scikit-learn Pipelines were used. Separate pipelines were created for numerical and categorical features. These pipelines were then combined using ColumnTransformer, which allows different transformations to be applied to different columns automatically. This approach makes the code clean, structured, and easy to maintain.

The final stage was the Load phase. After transformation, the processed data was converted into a final dataset and saved as a new CSV file named processed_data.csv. This file contains clean and transformed data that can be directly used for machine learning models, analysis, or visualization tasks.

This ETL pipeline has many practical applications. It can be used for automating data preprocessing, preparing datasets for predictive modeling, cleaning survey data, and handling large datasets efficiently. Such pipelines are commonly used in industries like finance, healthcare, e-commerce, and data analytics.

Through this task, I gained practical experience in working with real datasets and learned how to design an end-to-end ETL pipeline. I understood the importance of preprocessing and how automated pipelines improve efficiency and reduce manual effort. This task helped strengthen my understanding of data processing concepts and provided hands-on exposure to tools widely used in the industry.

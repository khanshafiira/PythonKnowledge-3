# Python for Beginner
If you are curious about Python programming and want to learn more about it, sure, this page may suit you!

This README will provide you a clear grasp of some important fundamental in Python, making your learning experience more enjoyable and straightforward.

Anyway, you can check the previous one to elaborate what we learn about Python for Beginner: https://github.com/khanshafiira/PythonKnowledge-1

Happy growing!

## Data Analytics
Data analytics transforms raw data into actionable insights. It encompasses a variety of techniques, technologies, and methods used to identify trends and solve problems utilizing data. Data analytics may help influence corporate processes, improve decision-making, and drive growth.

### 1. Data Basics

#### The Concept of Data
Data is collected, stored, and analyzed as qualitative or quantitative information in various forms. It can be structured, organized in a specific format, or unstructured. In computing and technology, data is used for insights, decision-making, and problem-solving through data analysis and mining.

#### Basic Data Variable Types
a) Numbers (Integer, Float, and Complex)
b) Boolean
c) String

#### Basic Structures Used in Data Analytics
The data structures differ according to mutability and order. There are so many basic structures when we used it for data analytics. But, in Phyton, the essential data structures that we must know are:

a) Table (DataFrame)

Table creates a Table object for displaying comprehensive data. The data is organized into a grid of rows and columns. Most styles can be applied to headers, columns, rows, or individual cells.

Example:

<img src="https://github.com/khanshafiira/PythonKnowledge-3/assets/166186201/b4725758-86ca-4ef1-b7f7-6b4b13366dff" width="700" height="210">

#Notes
 
The table is from Titanic's Dataset, access the dataset here:  https://github.com/khanshafiira/PythonKnowledge-2/blob/main/Titanic.csv

b) Row

Row is a read-only dictionary-like structure that stores the cell values for a single row. As seen in the sample above, the values can be accessed by using the column name and the standard Python square bracket lookup method. The value of a cell in column 'Age' is obtained as follows: `>>> row['Age']`.

c) Column

Columns is an attribute that allows you to retrieve a DataFrame's column labels. It returns an index object that represents the names of the columns in the dataframe.

#### Data Categories
1. Quantitative Data
   
   Quantitative data is numbers-based, countable, or measurable; informs us how many, how much, or how often in computations. Quantitative data is examined using statistical methods and also it is fixed and universal.
   
   Example: age, height, weight, income, number of errors, etc.
   
2. Qualitative Data
   
   Qualitative data is interpretation-based, descriptive, and related to language. It can help us understand why, how, or what transpired behind specific behaviors. Qualitative data is studied by classifying the data into categories and topics, subjective, and unique.
   
   Example:
   
   - gender, religion, marital status, native language, social class, etc.
   - <img src="https://github.com/khanshafiira/PythonKnowledge-3/assets/166186201/6f76d405-ec15-4f94-93b6-db70c688047f" width="450" height="250">

3. Structured Data
   Structured data stands for information that is highly organized, factual, and to-the-point. It usually comes in the form of letters and numbers that fit nicely into the rows and columns of tables.
      
4. Unstructured Data
   Unstructure data doesn't have any predefined structure to it and comes in all its diversity of forms.
   
5. Metadata
   Metadata is defined as the data providing information about one or more aspects of the data; it is used to summarize basic information about data that can make tracking and working with specific data easier.
   
   Example:
   
   <img src="https://github.com/khanshafiira/PythonKnowledge-3/assets/166186201/88960984-8c5a-4163-9431-84e1dbe1b633" width="450" height="350">
   
   .

   Source: https://opendata.jabarprov.go.id/id/dataset/jumlah-penduduk-berdasarkan-agama-kepercayaan-di-jawa-barat

6. Big Data
   
   Big data refers to large, complex, and diverse collections of structured, semi-structured, and unstructured data that continue to grow exponentially over time.

### 2. Data Manipulation
Data manipulation refers to the process of transforming and restructuring data to make it suitable for analysis or visualization. Pivot tables are a common technique used in data manipulation, especially for summarizing and aggregating data in a structured format.

#### Import, store, and export data
<img src="https://github.com/khanshafiira/PythonKnowledge-3/assets/166186201/ea7d7c20-51d5-4c19-a19e-038de247c9c1" width="220" height="150">

#### Clean Data
Data cleaning in Python refers to the process of identifying and correcting errors, inconsistencies, and inaccuracies in a dataset to improve its quality and reliability for analysis or other purposes. It involves various tasks such as handling missing values, removing duplicates, correcting inaccuracies, and standardizing formats.

#### Organize Data
1. Slicing
2. Sorting
3. Filtering
   
#### Aggregate Data
1. Pivoting
2. Grouping
3. Joining/merging
4. summarizing

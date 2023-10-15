# IT-SPESIALYST-DATA-ANALYSTT
# Import, Store, Export Data
Extract, transform, and load (ETL) is the process of combining data from various sources into a large central repository called a data warehouse. ETL uses a set of business rules to clean and organize raw data and prepare it for storage, data analytics, and machine learning (ML). You can meet specific business intelligence needs through data analytics (such as predicting the outcomes of business decisions, generating reports and dashboards, reducing operational inefficiencies, and more). The first stage of ETL is to perform Extract, which is a stage for retrieving data from existing data sources such as text files, spreadsheets, etc. For example, we have uploaded a CSV file in Jupiter which we put together in a PYTHON folder, secondly by carrying out a transformation, which involves processing and modification.
The data has been entered into Jupiter so that the data we will use is in accordance with the analysis needs. This data transformation is used to clean, combine and change
data structures if necessary. And the Load Stage is the stage of storing the processed data in the repository which will be used for further analysis. So at this load stage we can process the data that we have processed
Save it using the source code as above, in order to carry out further data analysis.
# Clean Data
Clean data is a stage used to clean data from common problems such as NULL values, special characters, unnecessary spaces, inconsistent formats, and duplicate data. This stage is necessary so that the data can be processed further without deficiencies and errors. The first stage of the data clean process is Handling NULL, namely the data cleaning process to replace NULL (empty values) with default values. To find out which columns have Null (empty values), you must first look at the information from the data to be processed. You can see that there are columns that have null values, namely the power, fuel, gear and version columns. The next stage is special characters which are carried out to remove unwanted special characters. The third stage of Trimming Spaces is carried out to remove unnecessary spaces in the column. Inconsistent Formatting is done to change data to be consistent according to the data type. Removing duplicates is done to delete duplicate data. and finally Imputing data, namely saving data that has been cleaned, for example saved in CSV form. And there is the Validating data stage in data manipulation, which is a process of checking whether the data meets certain criteria or rules before further analysis or processing is carried out. This is very important to ensure the accuracy and integrity of the data.
# Organize Data
Data organization (arranging data) is the process of putting data into groups and categories to make it easier to use so that it can be accessed, processed and analyzed more quickly. The first stage is Sorting, which is a process of rearranging a collection of objects using certain rules. Sorting is also referred to as an algorithm for placing a collection of data elements into a certain order based on one or several keys in each element. The second stage is the Filtering process, which is the process of examining a data set to exclude, rearrange, or divide data according to certain criteria. Next, the Slicing process is an operation used to access a portion of
a sequence (sequence) such as a string, list, or tuple. This
allows you to select a subset of data from a larger sequence by specifying start and end indices. Transposing is an operation that changes the position of a row
column and vice versa in a data or matrix. Appending is one of the features in python arrays which is quite
Often used is the append function. This append function is useful
to add the array value at the end. The final stage of the Truncating process is a data manipulation operation that is used to remove some data from the beginning or end of the dataset. This is useful when you want to limit or truncate the data in your dataset according to certain conditions.
# Aggregate Data
Aggregate Data is the process of combining and summarizing data from various sources to produce in-depth conclusions known as data aggregation. The purpose of data aggregation is to facilitate the analysis and interpretation of large amounts of data. The first stage is to carry out the Grouping process, which is a technique for separating data based on criteria
specifically by mapping data with groups. To perform grouping, use a method called groupby (). When doing grouping there are several sequential processes such as splitting, playing and combining. The second process stage is Joining/merging, which is the process of combining two or more datasets based on certain keys or columns. This allows us to combine data from several different sources into one larger and more complete dataset. Summarizing is a way to summarize a document into a simpler form by taking the important points in the document. And the final stage Pivoting is one type of data visualization that is widely used and is the basic plot type in data visualization. This type of plot displays information in the form of a series of data points connected by straight line segments.

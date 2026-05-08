# DATA PROCESSING PIPELINE(Mockaroo - JSON - DataFrame - CSV)
---
A simple data workflow project that demonstrates how to generate random data from Mockaroo, process it using Google Colab, and transform it into a useful format that can be easily analysed 

## Project Overview
The section shows a step-by-step overview of the data pipeline :

1.Generate random dataset using [Mockaroo](https://www.mockaroo.com/?utm_source=chatgpt.com)
2.Create a repository and push the data to github
3.Import the raw dataset from github into google colab
4.Convert the data into Python List format
5.Slice the list
6.Convert list to a dataframe
7.Convert dataframe to CSV file

## Tools and technologies
-Gitbash
-Python
-Pandas
-Requests
-JSON
-Google Colab
-Mackaroo

### Workflow steps

- Visit [Mockaroo](https://www.mockaroo.com/?utm_source=chatgpt.com) and create a custom dataset schema based on your required fields.

- Generate the dataset and download it locally in JSON format.

- Create a GitHub repository and upload the dataset file to it using Git commands.

- Copy the raw file URL from GitHub to allow external access to the data.

- Set up a Google Colab notebook environment for data processing.

- Import the necessary Python libraries:
  - `requests` for fetching data from the URL
  - `pandas` for data manipulation and analysis

- Use the `requests` library to fetch the dataset from the GitHub raw URL.
 
- Convert the response into JSON format for Python processing.

- Convert the JSON data into a Python list.

- Slice the dataset to extract the top 10 records.

- Convert the sliced data into a Pandas DataFrame.

- Perform basic inspection using `.head()`.

- Export the final DataFrame into a CSV file for storage or further analysis.

  SUMMARY
  The project demonstrates a simple data engineering pipeline project
  (Mockaroo - JSON - DataFrame - CSV)
  ---
  Author
  
  Jesse Kenson
  
  Build as part of a data engineering learning project

   




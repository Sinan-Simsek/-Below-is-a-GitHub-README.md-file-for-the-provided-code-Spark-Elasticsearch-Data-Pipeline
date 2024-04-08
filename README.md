# Spark Elasticsearch Data Pipeline

This repository contains a Spark Elasticsearch data pipeline script that demonstrates how to read data from CSV files using Spark, process it, and then write it to Elasticsearch for further analysis. Additionally, it shows how to read data from Elasticsearch back into Spark for analysis.
Installation
To run this script, you'll need Python, Apache Spark, Elasticsearch, and the necessary Python libraries installed. Follow the steps below to set up the environment:

# 1.	Activate your Python virtual environment:

source ~/venvspark/bin/activate 

# 2.	Install the required libraries:

pip install elasticsearch==7.9.0 

# 3.	Set up Apache Spark:

# Assuming Spark is installed at /opt/manual/spark findspark.init("/opt/manual/spark") 

# 4.	Ensure Elasticsearch is running on your local machine.

# Usage
## 1.	Run the script:

python spark_elasticsearch_pipeline.py 

## 2.	The script will perform the following tasks:
•	Read data from a CSV file into a Spark DataFrame.
•	Preprocess the DataFrame (remove null values, convert data types, filter data).
•	Create Elasticsearch index mappings.
•	Write the processed DataFrame to Elasticsearch.
•	Read data from Elasticsearch back into Spark for further analysis.

#Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
License
This project is licensed under the MIT License.


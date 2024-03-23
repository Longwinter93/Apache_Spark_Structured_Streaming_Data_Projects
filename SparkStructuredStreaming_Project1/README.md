# MAIN GOAL OF PROJECT
<br />The main goal of this project is to use **Spark Streaming** to process data in real-time from csv files and save output data as parquet and json files.

## **SHORT DESCRIPTION OF PROJECT**
<br />A CSV file was splitted into a few csv files.
<br />**Streaming DataFrame** was created to represent the stream of inputing data (csv files). 
<br />**Spark Streaming** engine processes incoming data from this csv files in the **Streaming DataFrame**. 
<br />**Streaming DataFrame** without any aggregations with streaming data was saved as parquet files.
<br />A few operations was performed on **Streaming DataFrame** for example aggregations.
<br />This **Streaming Dataframe** with aggregation was placed in an in-memory table. 
<br />**Streaming DataFrame** with aggregation was saved as json and parquet files.


## **FINAL RESULT OF PROJECT**
<br />Data was processed in real-time in **Streaming DataFrame** from csv files _input source_ and output data was saved as JSON  and parquet files.
<br />_Output sinks_ (file sink) data without aggregations was stored in a OutputNoAgg folder, while output of data with aggregations was saved as a JSON file and a parquet file.
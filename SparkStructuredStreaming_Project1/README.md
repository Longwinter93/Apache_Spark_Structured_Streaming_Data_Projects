# MAIN GOAL OF PROJECT
<br />The main goal of this project is to use **Spark Streaming** to process data in real-time from csv files and save output data as parquet and json files.

## **SHORT DESCRIPTION OF PROJECT**
<br />A CSV file was splitted into a few csv files that are located in a
[InputStreamingData](https://github.com/Longwinter93/Streaming_Data_Projects/tree/main/SparkStructuredStreaming_Project1/InputStreamingData) folder.
<br />**Streaming DataFrame** was created to represent the stream of inputing data (csv files). 
<br />**Spark Streaming** engine processes incoming data from this csv files in the **Streaming DataFrame**. 
<br />**Streaming DataFrame** without any aggregations with streaming data was saved as [parquet](https://github.com/Longwinter93/Streaming_Data_Projects/tree/main/SparkStructuredStreaming_Project1/OutputNoAgg) files.
<br />A few operations was performed on **Streaming DataFrame** for example aggregations.
<br />This **Streaming Dataframe** with aggregation was placed in an in-memory table. 
<br />**Streaming DataFrame** with aggregation was saved as json [json](https://github.com/Longwinter93/Streaming_Data_Projects/blob/main/SparkStructuredStreaming_Project1/GroupingDeutschlandCityStreaming.json) and [parquet](https://github.com/Longwinter93/Streaming_Data_Projects/blob/main/SparkStructuredStreaming_Project1/GroupingDeutschlandCityStreaming.parquet) files.


## **FINAL RESULT OF PROJECT**
<br />Data was processed in real-time in **Streaming DataFrame** from [csv files](https://github.com/Longwinter93/Streaming_Data_Projects/tree/main/SparkStructuredStreaming_Project1/InputStreamingData) _input source_ and output data was saved as JSON  and parquet files.
<br />**Output sinks** (file sink) data without aggregations was stored in a [OutputNoAgg](https://github.com/Longwinter93/Streaming_Data_Projects/tree/main/SparkStructuredStreaming_Project1/OutputNoAgg) folder, while output of data with aggregations was saved as [JSON](https://github.com/Longwinter93/Streaming_Data_Projects/blob/main/SparkStructuredStreaming_Project1/GroupingDeutschlandCityStreaming.json) and [parquet](https://github.com/Longwinter93/Streaming_Data_Projects/blob/main/SparkStructuredStreaming_Project1/GroupingDeutschlandCityStreaming.parquet) files.


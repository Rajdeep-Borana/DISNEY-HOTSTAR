# DISNEY-HOTSTAR
We have Designed ETL pipelines that extract and load data seamlessly. we have developed ETL pipelines using Apache Spark with Scala programming language and configuring YAML files to enable data extraction from various batch sources in one of the online video streaming platform Disney Hotstar

**YAML Configuration File:-**
1. Create a YAML configuration file that defines the various data sources, target layer, and transformations to be applied.
2. The YAML file should include details such as source connection information, target connection information, and transformation rules.[Uploading data.yaml…]()

   
**Apache Spark with Scala:-**
1. Use Apache Spark, a fast and distributed data processing engine, to implement the ETL pipeline.
2. Scala, a programming language compatible with Spark, will be used to write the pipeline code.

**Data Extraction:-**
1. Read the YAML configuration file to extract the details of the data sources.
2. Use Spark's built-in connectors or custom connectors to extract data from various sources such as databases, JSON, Parquet, CSV files etc.

**Data Transformation:-**
1. Apply the defined transformations to the extracted data.
2. Use Spark's DataFrame API or Spark SQL to perform transformations like filtering, aggregations, joins, etc.
3. The transformation rules can be defined in the YAML file, specifying the operations to be performed on the data.

**Data Loading:-**
1. Read the target layer details from the YAML configuration file.
2. Use Spark's connectors or custom connectors to write the transformed data to the target layer such as databases, JSON, Parquet, CSV files etc.

**Error Handling and Monitoring:-**
1. Implement error handling mechanisms to handle any exceptions or failures during the ETL process.


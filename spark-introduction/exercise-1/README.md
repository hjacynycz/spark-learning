# Spark RDD exercise

### Complete the following tasks using only RDDs API

1. Read the log file.
2. Obtain and print: total number of lines, chars and first few lines.
3. Separate the line into a tuple.
4. Calculate the number of logs per country. Show top 3.
5. Calculate the number of logs per type.
6. Show the date when the errors started and show the country.
7. Show the country with more errors and the amount detected.

### Repeat the same tasks using DataFrame/Dataset API

___You can submit your results via Pull Request___


### Follow this steps to run the script:  
`mvn clean package`  
`spark-submit --class com.spark.example.Examples target/rdd-examples-1.0-SNAPSHOT.jar`  

___$SPARK_HOME and $JAVA_HOME should be set, and $SPARK_HOME/bin on $PATH___  

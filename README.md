# WordCount-Program-in-Hadoop

Implementing WordCount Java program in Hadoop HDFS

The following commands can be used to run the file in Ubuntu Linux:

To put the files in a specific directory hadoop fs -put '/home/hdoop/input_file2.txt' /WordCountTutorial/Input

To run the jar file hadoop jar '/home/hdoop/wordcount.jar' WordCount /WordCountTutorial/Input /WordCountTutorial/Output

To see the output hdfs dfs -cat /WordCountTutorial/Output/part-r-00000


# DevOps pipeline for Real Time Social/Web Mining

## Workflow 

![Workflow](img/Workflow.png)

[x] Setting up Apache Maven for Java project - User Interface and MapReduce functions

[x] Setting up GitHub repository workflow

[x] Setting up GitHub Actions for automation

[x] Creating a web crawler in Python using Tweepy library to fetch data based on some parameter.

[] Create a User Interface

[x] Create a HDFS cluster for MapReduce functionality and program Hadoop MapReduce in Java

[x] Setup HDFS in MapReduce in Java and include Hadoop MapReduce JAR file

[x] Automate the Big Data pipeline till MapReduce using GitHub Actions

[] Use Data Ingestion tools like Flume to send data from crawler to HDFS at real time

[x] WAP in Java to implement MapReduce from JSON file extracted from crawler to find the frequency of significant words - Textual Analysis

[] Data Classification - create a multi-class data dictionary for sentimental analysis - currently for words (in future, we might extend it for phrases and sentences for improved accuracy)

[x] Data Predicition - Using the KNN algorithm in Python to find the relation between tweets and their sentiments.

[x] Data Visualization - Using the Python **matplotlib** library to implement visualization.

## Important Source files and dependencies

1. [pom.xml](pom.xml) - Setup Apache Maven

2. [helloworld.java](src/main/java/pkg/HelloWorld.java) - Basic Java project setup

3. [maven.yml](.github/workflows/maven.yml) - setup GitHub Actions

4. [crawler.py](src/crawler/Crawl.py) - Web Crawler in Python to extract twitter data based on specific hashtags.

5. [info.csv](src/crawler/info.csv) - data file created as an output for the crawler and to be sent to the HDFS core for processing

6. MapReduce functionalities in Java

* [Map Function](src/main/java/pkg/Map.java)
  
* [Reduce Function](src/main/java/pkg/Reduce.java)
  
* [Main Java Code](src/main/java/pkg/WordCountDriver.java)
  
7. [Sentimental Analysis in Python](src/sentimental_analysis)

* Convolutional Neural Networks
* Decision Tree
* SVM
* Pre-Processing
* Random Forests
* Naive Bayes
* XGBoost

8. [matplotlib.py](src/visualization/matplotlib.py) - Data Visualization using matplotlib in python

## How to Contribute

It is an open source project. Open for everyone.

Follow these contribution [guidelines](CONTRIBUTING.md).

## License

MIT [License](LICENSE), copyrighted to Storms In Brewing (2019-2020) 

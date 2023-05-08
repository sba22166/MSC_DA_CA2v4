# MSC_DA_CA2v4
CA2 - Big Data &amp; Advanced Data Analysis


Students are advised to review and adhere to the submission requirements documented after the assessment task.
In this continuous assessment, You are required to identify and carry out an analysis of a large dataset gleaned from the twitter API. Instructions for accessing the data can be found here
https://datascienceparichay.com/article/get-data-from-twitter-api-in-python-step-by-step-guide/
https://www.toptal.com/apache/apache-spark-streaming-twitter
OR You may use the data held here:
https://archive.org/details/twitterstream?sort=-publicdate
You must collect at least 1 year's tweets on a topic, this data should be stored as requested below, and you are then required to analyse any change sentiment that occurs over the time period that you have selected.
Following your analysis, you are then required to make a time series forecast of the sentiment at 1 week, 1 month and 3 months going forward. This forecast must be displayed as a dynamic dashboard.     
You may choose any topic that you wish to analyse EXCEPT for crypto-currency and financial or commodity stocks. You may not use any topic used previously in any Assessment.
Your project must incorporate the following elements:
●	Utilisation of a distributed data processing environment (e.g., Hadoop Map-reduce or Spark), for some part of the analysis.
●	Source dataset(s) can be stored into an appropriate SQL/ NoSQL database(s) prior to processing by MapReduce / Spark (HBase / HIVE / Spark SQL /Cassandra / MongoDB / etc.) The data can be populated into the NoSQL database using an appropriate tool (Hadoop/ Spark etc.)
●	Post Map-reduce processing dataset(s) can be stored into an appropriate NoSQL database(s) (Follow a similar choice as in the previous step)
●	Store the data and then follow-up analysis on the output data. It can be extracted from the NoSQL database into another format, using an appropriate tool, if necessary (e.g. extract to CSV to import into R/ Python etc.).
●	Devise and implement a test strategy in order to perform a comparative analysis of the capabilities of any two databases (MySQL, MongoDB, Cassandra, HBase and CouchDB) in terms of the performance. You should record a set of appropriate metrics and perform a quantitative analysis for comparison purposes between the two chosen database systems.
●	Provide evidence and justification of your choice of sentiment extraction.
●	Explore time-series forecasting and evidence and justify your choices and final analysis including your forecasts at  1 week, 1 month and 3 months.
●	Your dashboard must be dynamic and interactive. Include your design rationale.


Deliverables:
The results of the analysis must be presented in the form of a project report. This report should discuss the storage and processing of big data using advanced data analytics techniques. The report should be 3000 ± 10% words in length (excluding references, titles and code) and must follow the Harvard styles format in addition to employing appropriate referencing methods and academic writing style. The report should include the following:
1.	Details of the data storage and processing activities carried out, including preparation of the data and processing the data in a MapReduce/ Spark environment;[0-20]
2.	A discussion of the rationale and justification for the choices you have made in terms of data processing and storage, programming language choice, machine learning models and algorithms that you have implemented.[0-40]
3.	Comparative analysis for at least two databases using any benchmarking tool. (For example, ycsb)[0-10]
4.	Your analysis of  any change sentiment that occurs over the time period that you have selected.[0-10]
5.	Your forecast of the sentiment at 1 week, 1 month and 3 months going forward[0-10]
6.	Presentation of results by making appropriate use of figures along with caption, tables, etc and your dashboard for your forecast.[0-10]
Note that MapReduce-style processing in this instance is considered to include platforms such as Apache Spark.
Marks and feedback will be provided for each module separately based upon the learning outcomes for each of the modules.  
All documentation, code, examples, and any other files MUST be evidenced in your Version Control repository. (Git or Similar) using your CCT email address ONLY. Your repository MUST show your continual development of the project throughout its lifecycle and include notes detailing progress at each commit.
![image](https://user-images.githubusercontent.com/120040771/236909334-f3938219-142e-47e4-b679-7fc8d7cdc39a.png)

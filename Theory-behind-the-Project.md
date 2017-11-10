## ABSTRACT

Big Data is any set of data that is too large to be processed by traditional processing methods. With the spread of Information Technology and with the increase in the amount of data going digital since the 1990s, handling Big Data efficiently became an issue for universities and corporates alike as the data produced increased in volume with every passing year. Relational Database Systems were unable to handle this data as many parallel servers with considerable processing power would be required to achieve efficient speeds. This prompted the establishment of more specific data mining techniques capable of handling and analysing large datasets. Nowadays, big data mining contributes valuable insight into almost any corporate entity’s business plan, any university’s course curriculum, and is even involved in every Google Search. Handling of big data sets is a problem that many big companies face today. Big data has increased the demand of information management specialists so much so that software AG, Oracle Corporation, IBM, Microsoft, SAP, DMC, HP, and Dell have spent more than $15 billion on software firms specializing in data management and analytics. Through the course of this project, use of data mining techniques to analyze open source data sets, is going to be explored. Also a graphical analysis of certain parameters in the data set will be presented. The most efficient algorithms for data mining shall be employed and easy-to-use graphical interface shall be utilized for the benefit of the user. 

## 1.	Introduction
### 1.1 Theoretical Background
Big data is a term for data sets that are so large or complex that traditional data processing software are inadequate to deal with them.  
•	Some of the challenges include capture, storage, analysis, data curation, search, sharing, transfer, visualization, querying, updating and information privacy. 
•	The term "big data" often refers to the use of predictive analytics, behavior analytics, or certain other advanced data analytics methods that extract value from data, but rarely to a particular size of data set. 
•	Analysis of data sets can be used to spot business trends, prevent diseases, predict crimes etc.
•	Developed economies increasingly use data-intensive technologies. There are 4.6 billion mobile-phone subscriptions worldwide, and between 1 billion and 2 billion people accessing the internet. 
*	Between 1990 and 2005, more than 1 billion people worldwide entered the middle class, which means more people became more literate, which in turn lead to information growth. 
*	The world's effective capacity to exchange information through telecommunication networks was 281 petabytes in 1986, 471 petabytes in 1993, 2.2 exa-bytes in 2000, 65 exa-bytes in 2007 and predictions put the amount of internet traffic at 667 exa-bytes annually by 2014. 
*	According to one estimate, one third of the globally stored information is in the form of alphanumeric text and still image data, which is the format most useful for most of the big data applications.

### Characteristics of Big Data:
#### Volume: 
Quantity of stored and generated data; the size determines whether the data set can be considered as “big data” or not.
#### Variety:
Type and nature of data.
#### Velocity: 
Speed with which data is generated and processed to meet demands of users .

### 1.2 Motivation
There are over four billion mobile phone subscriptions in the world and almost 70% mobile phone users have access to the internet.
*	This means that there’s terabytes of data generated/replicated and moved everyday.
* To handle this massive amount of data we need proper management of data.
*	Thus as budding responsible engineers it is our responsibility that we contribute to a solution for this problem

### 1.3 Aim of the proposed work
The aim is to mine data from a data file using big data mining tools or methods. Also we want be to interpret and graph the data in the data file.

### 1.4 Objectives of the proposed work
In accordance with our project aim, we had to choose a data mining tool that satisfied the following criteria: -
*	Easy to implement
*	Easy to use
*	Fast processing of the data (Time complexity should be less)
*	System requirements should be minimal
*	Less space and memory utilisation

The tool chosen for data mining:
Apache’s Hadoop is the tool that we have chosen to implement big data analysis of our data set.

#### 1.5	Report Organization
a) Establishing a data mining tool to implement big data mining upon
*	Learn about the basics of big data analysis
*	Find out what the requirements are for choosing a suitable data mining tool
*	Find out about the implementation details of each suitable candidate
*	Choose the one that’s easiest to use while fulfilling criteria like speed, functionality and so on

b) Choosing a suitable data file for efficient and useful data mining to be performed
*	The other key to data mining is that the data file that is to be mined must be worth mining.
*	Many open source data files are available online. 
*	Out of these, it is our task to choose a data file that can be used to better any aspect of a current situation

c) Choosing a suitable graphing tool
*	To make the mined data and the output generated more appealing to an end user, interactive graphs are necessary
*	A simple, easy-to-use tool is required
*	At the same time, it must be powerful enough to execute any of the graphs based on what the outputs are



## 2. Literature Survey
### 2.1 Survey of the existing Models/Work
Big data became an important issue for almost every corporate entity in the world from   the early 1990s. With the available processing power at that time, it was close to impossible to analyse all of the data in one go from a single system or from even a server. 
This is where methods such as clustering and others which are described in the slides to follow became increasingly important.

Classical techniques of Data mining:

The classical techniques used for data mining are
* Statistics:
Used long before the term data mining was coined to apply to business applications.
Statistical techniques are driven by the data and are used to discover patterns and build predictive models.
Statistics is a branch of mathematics concerning the collection and the description of data.
One thing that is always true about statistics is that there is always data involved,  and usually enough data so that the average person cannot keep track of all the data in their heads.   This is certainly more true today than it was when the basic ideas of probability and statistics were being formulated and refined early this century.

*	Neighborhoods/Nearest Neighbor:
Nearest neighbor prediction technique is one of the oldest techniques used in data mining. Nearest neighbor is a prediction technique that is quite similar to clustering. In order to predict what a prediction value is in one record look for records with similar predictor values in the historical database and use the prediction value from the record that it “nearest” to the unclassified record.

*	Clustering:
Clustering is the method by which like records are grouped together.
Usually this is done to give the end user a high level view of what is going on in the database.
Clustering is sometimes used to mean segmentation - which most marketing people will tell you is useful for coming up with a birds eye view of the business.
This clustering information is then used by the end user to tag the customers in their database.


## 3.	Overview of the proposed system

### 3.1 Introduction
The tool chosen for data mining:

Apache’s Hadoop is the tool that we have chosen to implement big data analysis of our data set.
   So now what exactly is Hadoop?

   The Apache Hadoop software library is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models.

Easy to Implement:
Hadoop clusters are easy to implement and there is sufficient documentation and other details that can be found on the internet.
Versatility:
A Hadoop cluster can consist of one or more individual nodes, and the languages available in  for implementation.

### 3.2	Framework, Architecture and Modules for the Proposed System(with explanation)
Hadoop Distributed File System (HDFS):
* Array of storage clusters that holds the actual data
*	By default Hadoop uses Hadoop Distributed File System though it can use other file systems as well
*	HDFS is like the bucket of the Hadoop system: You dump in your data an it stays there until you want to do something with it like analyzing it or capturing and exporting a set of data to another tool.

Data Processing Framework and MapReduce:
*	It’s the tool used to work with the data itself. By default, this is the Java-based system known as MapReduce.
*	In a “normal” relational database, data is found and analyzed using queries, based on Structured Query Language (SQL).
*	But Hadoop is like a data warehousing system. It stores data and you can pull data from it.
*	So it needs a system like MapReduce to process the data


### 3.3 Proposed System 
  The MapReduce:
*	MapReduce runs as a series of jobs, with each job essentially a separate Java application that goes out into the data and starts pulling out information as needed.
*	Using MapReduce instead of a query gives data seekers a lot of power and flexibility, but also adds a lot of complexity.
*	There are tools to make this easier: Hadoop includes Hive, another Apache application that helps convert query language into MapReduce jobs.

Working of the MapReduce:
1.	The Map part is accomplished by the JobTracker dividing computing jobs up into defined pieces
2.	Jobs are shifted out to the TaskTrackers on the machines out on the cluster where the needed data is stored. 
3.	Specific blocks of data are allocated to each reducer. 
4.	Each reducer works on performing the required operation (like sorting, searching, basic arithmetic, etc.) on its allocated data.
5.	Once the job is run, the correct subset of data is Reduced back to the central node of the Hadoop cluster, combined with all the other datasets found on all of the cluster’s machines (reducers).

Scattered Across the cluster:
*	The element that makes Hadoop unique: All of its functions act as distributed systems and not centralized systems.
*	All of the data sets on one or more machines, and all of the data processing software is housed on another server.
*	On a Hadoop cluster, the data within HDFS and the MapReduce system are housed on every machine in the cluster.
*	When a request for information comes in, MapReduce uses two components, a JobTracker that sits on the Hadoop master node, and TaskTrackers that sit out on each node within the Hadoop network.


# Introduction to Hadoop
### What is Hadoop?
Apache Hadoop is an open-source software framework
for storage and large-scale processing of data-sets on clusters of
commodity hardware.
* Created by Doug Cutting and Mike Cafarella in 2005
* Named the project after Doug son's toy elephant
* Hadoop moves computation to data
* Scalability is at its core
* Reliability: Hardware failures handled automatically
* New approach to data: We can keep all data

### The Apache framework basic
* Hadoop Common: Contains libraries and other utilities that are needed
by other Hadoop modules
* Hadoop Distributed File System: Stores data on the commodity machine
  * HDFS is a distributed, scalable, and portable filesystem written in
  Java for the Hadoop framework
* Hadoop MapReduce: Scales data across the different processes
* Hadoop YARN: Responsible for managing the computer resources in the
cluster. Focuses exclusively on scheduling
  * Introduced in Hadoop 2.0 in 2013

![hadoop](https://user-images.githubusercontent.com/31813625/36898033-1b750800-1de7-11e8-82d2-7ebf9f9bce97.png)

* YARN is extremely compatible with MapReduce.
* Improved cluster utilization according to the criteria such as:
  * Capacity
  * Guarantees
  * Fairness
  * different SLAs
* Supports other workloads other than only MapReduce
  * Graph processing
  * Iterative Modeling
  * Machine learning
  * Multiple Access Engines
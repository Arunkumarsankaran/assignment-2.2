Q1)HDFS
• The file store in HDFS provides scalable, fault-tolerant storage at low cost.
• The HDFS software detects and compensates for hardware issues, including disk problems and server failure.
• HDFS stores files across the collection of servers in a cluster.
• Files are decomposed into blocks and each block is written to more than one of the servers.
• The replication provides both fault-tolerance and performance.

Q2)Hadoop cluster
A Hadoop cluster is a special type of computational cluster designed specifically for storing and analyzing huge amounts of unstructured data in a distributed computing environment. 
Hadoop clusters are known for boosting the speed of data analysis applications. They also are highly scalable: If a cluster's processing power is overwhelmed by growing volumes of data, additional cluster nodes can be added to increase throughput. Hadoop clusters also are highly resistant to failure because each piece of data is copied onto other cluster nodes, which ensures that the data is not lost if one node fails.

Q3)HDFS blocks
Hadoop distributed file system also stores the data in terms of blocks. However the block size in HDFS is very large. The default size of HDFS block is 64MB. The files are split into 64MB blocks and then stored into the hadoop filesystem. The hadoop application is responsible for distributing the data blocks across multiple nodes. 

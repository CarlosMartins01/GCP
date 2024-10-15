
# <center>Storage</center>

### Cloud Storage

Cloud Storage = Object storage.
- Fully managed scalable service well suited for web apps. BLOB - Binary large-object.
- Files are organized into buckets.
- The storage objects are “immutable,” which means that you do not edit them. "version it" - it keeps a record of modifications.
- Control access to data objects with IAM roles and ACLs
- Cloud Storage can also be used like a file system. Linux and Mac.
- Lifecycle management policies save money. Use it!

Cloud Storage Classes "4"
- Standard Storage  - Hot data.
- Nearline Storage  - Once per month.
- Coldline Storage  - Once every 90 days.
- Archive Storage   - Once a year.

AutoClass
Autoclass automatically transitions objects to appropriate storage classes.

Bring data into Cloud Storage
- Online transfer.
- Storage Transfer Service.
- Transfer Appliance.

Integration with other Google Cloud products.


### Cloud SQL

Cloud SQL = Ralational Database Management.
- Cloud SQL offers fully managed relational databases, including MySQL, PostgreSQL, and SQL Server as a service.
- Cloud SQL instances is that they are accessible by other Google Cloud services, and even external services.


### Spanner

Spanner = Fully managed relational database.
- Scales horizontally, is strongly consistent, and speaks SQL.

Spanner is especially suited for applications that require:
- An SQL relational database management system with joins and secondary indexes.
- Built-in high availability.
- Strong global consistency.
- And high numbers of input/output operations per second. We’re talking tens of thousands of reads/writes per second or more.

### Firestore

Firestore = NoSQL "Document DB".
- Firestore is a ﬂexible, horizontally scalable, NoSQL cloud database for **mobile**, **web**, and **server development**.
- Firestore uses online and offline data synchronization.

Firestore leverages Google Cloud's infrastructure.
- Automatic multi-region data replication.
- Strong consistency guarantees.
- Atomic batch operations.
- Real transaction support.


### Bigtable

Bigtable = NoSQL big data database service.
- Work with more than 1TB of semi-structured or structured data.
- Data is fast with high throughput, or it’s rapidly changing.
- Work with NoSQL data.
- Data is a time-series or has natural semantic ordering.
- Work with big data, running asynchronous batch or synchronous real-time processing on the data.
- Run machine learning algorithms on the data.
- Use APIs to read and write data.
- Streaming data into Bigtable.

#### Comparing storage options

| Option | Best for | Capacity |
| :---------------: | --------------- | ------------------ |
| Cloud Storage | Storing immutable blobs larger than 10 MB. | Petabytes. Max unit size: 5 TB per object. |
| Cloud SQL | Full SQL support for an online transaction processing system. | Up to 64 TB. |
| | Web frameworks and existing applications. | |
| Spanner | Full SQL support for an online transaction processing system. | Petabytes. |
| | Horizontal scalabilityPetabytes. | |
| Firestore | Massive scaling and predictability together with real time query results and offline query support | Terabytes. Max unit size: 1 MB per entity.  | 
| Bigtable | Storing large amount of structured objects | Petabytes. Max unit size: 10 MB p/cell, 100 MB p/row. |
||Does not support SQL queries and multi-row transactions. ||
||Analytical data with heavy read and write events. ||




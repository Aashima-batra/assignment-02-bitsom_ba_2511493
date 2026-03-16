## Storage Systems

For the hospital data system, different storage systems are required for different types of data. A relational database such as PostgreSQL can be used to store operational data such as patient records, appointments, and treatments. This system supports fast transactions and updates which are required in hospital operations.

For analytical workloads, a Data Warehouse can be used to store historical hospital data. This allows hospital management to generate reports such as monthly bed occupancy, department costs, and patient statistics.

For real-time ICU monitoring data, a streaming system such as Apache Kafka can be used to collect continuous data from monitoring devices. This data can then be stored in a Data Lake for further analysis and machine learning model training.

## OLTP vs OLAP Boundary

The OLTP system includes the operational hospital databases where patient records, appointments, and treatments are stored. These systems focus on fast transaction processing and frequent updates.

The OLAP system begins when the operational data is extracted and loaded into the Data Warehouse or Data Lake. In this analytical environment, the data is used to generate reports and train machine learning models such as patient readmission risk prediction.

## Trade-offs

One trade-off of this architecture is increased system complexity. Multiple components such as databases, streaming systems, and analytical storage must be managed together.

This challenge can be addressed by using managed cloud services and automated monitoring tools that simplify deployment and maintenance.

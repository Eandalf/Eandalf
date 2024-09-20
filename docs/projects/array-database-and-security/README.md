# Array Database and Security (UROP 2019 Fall)

[Back to Home](../../../README.md).

Associated with The Hong Kong University of Science and Technology.

Feb. 2019 ~ Dec. 2019

This project aimed to research and analyze existing array databases, security issues among DBMS, and possible implementations for a secured array database. Spark, SciSpark, SparkArray, H5Spark, SparkSQL, and Opaque (a database based on SparkSQL with the protection of oblivious data operations) were surveyed in this project. After observing these existing systems, a secured array database was proposed in the report of this UROP (Undergraduate Research Opportunity Program) project. The proposed secured array database would be based on SciSpark with the tile as the basic storage unit. At the same time, queries would be processed by the secured enclave (Intel SGX) and oblivious operations supported in Opaque. Although the overhead to perform these secured computations was considerably huge, the secured array database still provided extraordinary protection to the data. If there was a scenario that huge array-like data required strong protection, the high overhead might be acceptable.

## WIP

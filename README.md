# golang-database-CRUD
1. The "main.go" is running the CRUD operations on indefinite Goroutines which are concurrent safe. <br />
2. CRUD operations are called in main.go file by entering a specific number for each function from the menu.
+ Achieve concurrency in Golang through Go routines (pggoconcurrency) <br />
+ Inserted 1,000,000 (million) records while achieving concurrency <br /> <br />
Here are the benchmarks and stress-test results. <br /><br />
**Benchmarks:** <br />
+ When inserted 100,000 records in 47,873,830.827 microseconds (47.8 seconds) in the Database and Read 100,000 records in 51,172.019 microseconds (0.051 seconds) (Go Language) ) <br />
+ Inserted 1,000,000 (million) records in 8 minutes and 41.788600694 seconds and Read 1,000,000 (million) records in 503,822.315 microseconds (0.5 seconds) (Go Language) ) <br /><br />
- When inserting 100,000 rows, it takes 744,964 microseconds on average, equivalent to 0.744964 seconds.
- Takes 10,387,597 (10.38 million) microseconds on average, equivalent to 10.3857 seconds to insert 1,000,000 (1 million) rows.
- To insert 2,000,000 (2 million) rows in the database, the insert operation takes 20,940,600 (20.94 million) microseconds on average, equivalent to 20.9406 seconds.
- The average time to insert a single row in the dataset with 100,000 rows is 0.0403 microseconds.
- The average time to insert a single row in the dataset with 1 million rows is 0.054686 microseconds.
- The average time to insert a single row in the dataset with 2 million rows is 0.033102 microseconds.
**Stress-test:** <br />
+ Performing concurrent CRUD operations seamlessly without encountering any errors. <br />

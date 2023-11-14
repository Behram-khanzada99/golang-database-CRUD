# golang-database-CRUD
1. The "main.go" is running the CRUD operations on indefinite Goroutines which are concurrent safe. <br />
2. CRUD operations are called in main.go file by entering a specific number for each function from the menu.<br />

Here are the benchmarks and stress-test results. <br /><br />
**Benchmarks:** <br /><br />
- When inserting 100,000 rows, it takes 2,844,964 microseconds on average, equivalent to 2.844964 seconds.
- To insert 1,000,000 (1 million) rows in the database, the insert operation takes 30,937,478.482 (30.93 million) microseconds on average, equivalent to 30.937478482 seconds.
- To insert 2,000,000 (2 million) rows in the database, the insert operation takes 61,816,881.154 (61.81 million) microseconds on average, equivalent to 1 minute 1.816881155 seconds.


**Stress-test:** <br /><br />
+ Performing concurrent CRUD operations seamlessly without encountering any errors. <br />
- The IDE and system work fine inserting upto 5,000,000 rows (7 million).
- The indefinite CRUD operations run fine when inserting up to 7 million rows.


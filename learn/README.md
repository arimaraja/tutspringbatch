# Tutorial is meant for hands-on spring batch.
## About SpringBatch
1. It is lightweight batch framework based on spring
2. Used for high volume batch processing
3. Have various IO options JSON, XML, SQL 
4. Able to manage with start/stop/restart options
5. Retry options are available.

## Key points in spring batch
1. Job: Jobs has multiple steps.
2. Step: Two types of step
	2.a Tasklet
	2.b chunk-oriented steps

## Ch1 First batch file.
1. Start spring initializer with following package
	a. spring batch io
	b. h2
2. Spring batch requires at-least one DB so we start with H2 database.
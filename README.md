# postgresql-issue-poc
PoC to reproduce the long delay at startup with postgreSQL driver v42.2.23

To run this PoC, first configure your data source in application.properties. Then, just run as a Spring application and see the delay in the console.

See [github issue](https://github.com/pgjdbc/pgjdbc/issues/2236).
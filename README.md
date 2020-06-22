# sample-spring-logback-janino-project
sample spring project which uses logback with janino for logging. 

logback.xml used instead of logback-spring.xml.

Logback is configured so that each log file will have maximum size of 10 MB.

Log files will be rolled over, compressed and kept in separate year and month folders.

Also, it is configured such that dev and prod profiles will have different log levels.

# Course Project

Updated the LogFileGenerator to be deployed on an instance of EC2 instance. 

Following changes are made
* Updated the logback.xml file to include the date with timestamp in the log messages. 
* All the logs will be deposited in a single log file `LogFileGenerator.log`

New Features:
* Earlier logs are deleted each time the LogFileGenerator is simulated. 
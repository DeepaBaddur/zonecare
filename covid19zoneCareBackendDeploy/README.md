# covid19ZoneCareBackend

This project provides backend APIs to zoneCareFrontEnd. It creates connection to DB2 database to access the data.

## Getting Started

To setup in the local, first install [Maven](https://maven.apache.org/install.html), to verify the installation,
```bash
mvn -version
# output
Apache Maven 3.5.4 (1edded0938998edf8bf061f1ceb3cfdeccf443fe; 2018-06-18T00:03:14+05:30)
Maven home: C:\maven\apache-maven-3.5.4-bin\apache-maven-3.5.4\bin\..
Java version: 1.8.0_11, vendor: Oracle Corporation, runtime: C:\PROGRA~1\Java\jdk1.8.0_11\jre
Default locale: en_US, platform encoding: Cp1252
OS name: "windows 8.1", version: "6.3", arch: "amd64", family: "windows"
```

Clone the covid19ZoneCareBackend, and import the existing maven project the IDE.

To run the maven application
```bash
mvn clean
mvn install
```

It will create the war in target folder, deploy the war in server and call the APIs.

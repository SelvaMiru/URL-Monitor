# URL-Monitor
Contains Maven Java Project on getting response as well as SSL details from a range of URLs

Description - 
Project: urlmonitor - reads and stores responses as well as certificate details from websites which are provided by an external input file (csv) and writes their output to another external (csv) file. Currently compatible with Unix based environments (due to use for WGET and CURL commands as failover).

Technologies used: JavaSE - 1.7
Build Tools Supported: Maven, Ant
Input File Name: urls.csv
Input File Format: ApplicationName,URL
Output File Name: urlPingResults
Output File Format: ApplicationName,URL,Status,ResponseCode,ResponseTime,ResponseMessage,CertificateExpiryDate,LastChecked,SSLVersion

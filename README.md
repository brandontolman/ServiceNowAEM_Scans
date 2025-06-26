# ServiceNowAEM_Scans
This is a scoped ServiceNow application to extend the App Engine Deployment & Pipeline application
Included in this application is a new pipeline copied off the OOB Application Deployment pipeline
This new pipeline behaves the same except for the Instance Scan and ATF behavior
There is a new subflow for deploying to a test environment which references a decision table for the ATF and Instance Scan 'scans'.
This decision table allows you to specificy different ATF and Instance Scan suites by application giving you greater control with your automated pipeline.

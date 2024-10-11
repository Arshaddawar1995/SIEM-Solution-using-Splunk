Security informations and Event Management System (Using Splunk Tool)
This project integrates Splunk for data analysis and visualization. It leverages Splunk's powerful capabilities to collect, index, and analyze machine-generated data.
Search the latest Version of Splunk and install it from Official website.
Splunk Universal forwarder tool is basically use to Locate the source and destination between server and client for logs and event managements.
Improve incident response capabilities through centralized log management and analysis.
•	Functionality Testing: Test the SIEM system to ensure proper functionality and integration with data sources.
•	Performance Validation: Validate the performance of the SIEM system, including log collection, event correlation, and alert generation.
./splunk start --accept-license
http://localhost:8000
index=main source="/var/log/syslog"

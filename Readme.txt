Security informations and Event Management System (Using Splunk Tool)
This project integrates Splunk for data analysis and visualization. It leverages Splunk's powerful capabilities to collect, index, and analyze machine-generated data.
Search the latest Version of Splunk and install it from Official website.
Splunk Universal forwarder tool is basically use to Locate the source and destination between server and client for logs and event managements.
./splunk start --accept-license
http://localhost:8000
index=main source="/var/log/syslog"

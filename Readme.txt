tar xvzf splunk-<version>-Linux-x86_64.tgz
cd splunk
./splunk start --accept-license
http://localhost:8000
index=main source="/var/log/syslog"

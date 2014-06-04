QPS_accessslog
==============

Script to get QPS from server access log


Command - cat access.log | cut -d "[" -f 2 | cut -d " " -f 1 | sort | uniq -c | sort -nr | grep "01/Apr/2014" > /tmp/output.txt

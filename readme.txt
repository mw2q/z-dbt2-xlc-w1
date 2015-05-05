Mon May  4 22:57:01 BST 2015
no thinktime
Linux ECSPGSQL 3.0.76-0.11-default #1 SMP Fri Jun 14 08:21:43 UTC 2013 (ccab990) s390x s390x s390x GNU/Linux
Command line: /home/mark/bin/dbt2-run-workload -a pgsql -c 10 -d 600 -w 1 -o z-dbt2-xlc-w1 -s 100 -z no thinktime -r -n -p -c max_connections=100 -c checkpoint_segments=180 -c checkpoint_timeout=30min -c shared_buffers=2GB -c work_mem=16MB
Database Scale Factor: 1 warehouses
Test Duration: 600 seconds
Database Connections: 10

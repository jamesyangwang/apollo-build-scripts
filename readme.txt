1. 'docker-compose up -d apollo-db' to start mysql server first, test with mysql client to make sure it's up and running.

2. 'docker-compose up -d apollo-quick-start' to start apollo services.

3. localhost:8070 - portal web

4. localhost:8080 - eureka services

5. localhost:8090 - admin services

* It takes time to start, wait and try again later...

6.  winpty docker-compose exec apollo-quick-start bash
	cd apollo-quick-start
	./demo.sh client
	timeout
	timeout
	quit

winpty docker-compose exec apollo-quick-start //bin/bash
winpty docker-compose exec apollo-quick-start //apollo-quick-start/demo.sh client

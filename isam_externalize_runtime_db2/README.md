Use the following commands to use this container:

To start the DB2 container:

docker-compose --file docker-compose-isamdb2.yml up -d

To terminate the DB2 container and delete all persistent data:

docker-compose --file docker-compose-isamdb2.yml down -v

To terminate the DB2 container and preserve all persistent data:

docker-compose --file docker-compose-isamdb2.yml down

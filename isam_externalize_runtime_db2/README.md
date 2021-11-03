
Introduction

The IBM ISAM 9.x appliance provides a feature known as Advanced Access Control, or AAC. For the virtual appliance form factor, this database resides upon the ISAM 9.x virtual appliance by default. However, for scaling and performance benefits, this database can be externalized to run on several database platforms. There is a documented manual process on how to perform this database externalization.

The purpose of this project is to provide a demonstration on how this manual process can be automated using Ansible and the ISAM REST API.

Docker Commands

Use the following commands to use this container:

To start the DB2 container:

  docker-compose --file docker-compose-isamdb2.yml up -d

To terminate the DB2 container and delete all persistent data:

  docker-compose --file docker-compose-isamdb2.yml down -v

To terminate the DB2 container and preserve all persistent data:

  docker-compose --file docker-compose-isamdb2.yml down

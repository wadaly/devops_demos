This directory contains resources for starting up an ISAM V9 Docker lab.

First, run bootstrap.yml as follows using docker-compose to create digital certificates for OpenLDAP and PostgreSQL.

> docker-compose --file bootstrap.yml up -d

> docker-compose --file bootstrap.yml down -v

Second, run isamlab.yml as follows using docker-compose to startup ISAM V9 Docker lab containers.

> docker-compose --file isamlab.yml up -d

If you do not have a license key to enable the ISAM web, AAC, and federation features, you may request a 90 day trial license key here:

> https://ibm.biz/isamtrial

The contents of this project are for learning and demonstration purposes and are not suitable for production deployment.

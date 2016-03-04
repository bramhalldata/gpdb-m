# Greenplum Database - Master Node Base
Pivotal Greenplum Database Base Docker Image (4.3.7.2)

# Building the Docker Image
This repository is used to auto-build the image which can be found at Docker Hub.

# Running the Docker Image
docker run -i -p 5432:5432 [tag]

# Container Accounts
root/pivotal

# Using pgadmin outside the Container
Launch pgAdmin3
Create new connection using IP Address and Port # (25432)

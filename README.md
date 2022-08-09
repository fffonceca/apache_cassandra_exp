# Cassandra Database in Python

## Objective
Creating a simple database with Cassandra Apache with python code. We will be using containers (Docker Style).

## Reference
For further information go to https://towardsdatascience.com/getting-started-with-apache-cassandra-and-python-81e00ccf17c9 all the theory come from there.

## Run example
Run the following example to simulate cassandra db:

    >docker-compose up -d
If you want to interact with the database, you should:

    >docker exec -it cas2  cqlsh
This allows to open a cqlsh shell on cas2 container (cas2 container corresponds to node2 in db). To end the simulation just run

    >docker-compose down


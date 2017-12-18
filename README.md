# Intro
Runs Docker Container with Neo4j 3.3.1 installed. GraphAware NLP and APOC plugins are also installed.

# Run
Run this container from within this directory:
```
[sudo] docker-compose up
```
Run in background from within this directory:
```
[sudo] docker-compose up -d
```

# Info
Neo4j container (named "neodb") will be up and running on ports localhost:7474 and localhost:7687. 

default initial username and password  
username: `neo4j`, password: `neo4j`

java runtime environment is set to run with 3gb of RAM. Up the size in `docker-compose.yml` for better performance. Docker container space will likely also need to be increased. Make sure to leave at least a 1gb slack space.

# Remove
To stop and remove the container:

```
[sudo] docker-compose down
```

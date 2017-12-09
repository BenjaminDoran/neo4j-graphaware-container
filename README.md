# Intro
Runs Docker Container with Neo4j 3.3.0 installed. GraphAware NLP and APOC plugins are also installed.

# Run
Run this container from within this directory:
```
[sudo] docker-compose up -d
```

# Info
Neo4j will be up and running on ports localhost:7474 and localhost:7687. 

java runtime environment is set to run with 3gb of RAM. Up the size in `docker-compose.yml` for better performance.

# Remove
To remove the container:

```
[sudo] docker-compose down
```


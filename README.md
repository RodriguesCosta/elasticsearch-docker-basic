# elasticsearch-docker-basic

## Steps

1. run ```docker-compose up -d```
2. run ```bin/elasticsearch-setup-passwords auto``` in elasticsearch container to generate passwords
3. run ```docker-compose down```
4. update passwords for user elastic in files ```apm-server.yml``` and ```kibana.yml```
5. run ```docker-compose up -d```

## Caution
This service not recommended for production, use this for development ambient or to capture logs in production, but is not very secure.

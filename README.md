# OpenAPI-Tutorial

Repository for the PCaPAC Tutorial session - OpenAPI

Install docker(compose) and run(neo4j database + openapi server):

If you are in the root project folder go to the code folder first, please. `cd code`
`docker-compose up -d --build`

To create data in DB use API endpoint /database/deleteAndInitNewData. For example from the docs: [API docs](http://localhost:3700)

## Running docker services:

tutorial-api: [localhost:3700](http://localhost:3700)

neo4j: [localhost:7474](http://localhost:7474)

(aditional service - run docker-compose-tools.yml)

swagger-editor: [localhost:3777](http://localhost:3777)

grafana: [localhost:3788](http://localhost:3788) (on Linux run: `sudo chown 472 $HOME/grafana-tutorial/data`)

# Systems database OpenAPI specification

[Download specification](https://raw.githubusercontent.com/JiriSvachaEliBeams/OpenAPI-Tutorial/main/code/systems-api/swagger/systemsapi.yaml)

# Useful tools and links

[OpenAPI initiative](https://oai.github.io/)

[OpenAPI specification](https://swagger.io/specification/)

[Swagger editor](https://editor.swagger.io/)

[List of OpenAPI tools](https://openapi.tools/)

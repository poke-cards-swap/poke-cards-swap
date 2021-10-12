# poke-cards-swap
Main repository for poke-cards-swap containing all parts of the project.
All microservices will be stored here as submodules, so they can be dockerized
for local testing. Although, it should be tested within staging environment
deployed to the cloud.

## Docs
In order to run docs you need Docker and docker-compose.

To run docs you need to run `docs` containers. In order to do that, you should type the following command:
```bash
$ docker-compose -f docker/docs/docker-compose.yml up --build
```
and go to http://localhost:3000.

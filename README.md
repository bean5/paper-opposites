# Opposites

Whitepaper on the topic of whether opposites (up/down, cat/dog) exist in the mainstream perspective.

## Dependencies

- docker
- docker-compose

## Build Instructions

```sh
docker-compose run proposal
docker-compose run final
```

The first time you run the command it will need to build the latex base image which can take a long time.

## To Do

- [ ] Use a common base image to accelerate first-time PDF generation

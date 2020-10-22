# DJTest

A base docker image for running tests related to DataJoint.

# Features

- Adds testing libraries:
  - nose
  - nose-cov
  - coveralls
  - flake8
- Applies image compresssion

# Launch locally

```shell
docker-compose -f dist/alpine/docker-compose.yml --env-file config/.env up --build
```

OR

```shell
docker-compose -f dist/debian/docker-compose.yml --env-file config/.env up --build
```


# Notes

https://hub.docker.com/r/datajoint/djtest
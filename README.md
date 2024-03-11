# dockerfiles

dockerfiles that can be used for different projects

```bash
docker build -t rosweb:melodic -f ./Dockerfile-rosweb-melodic .
docker run --rm --network host rosweb:melodic
```

```bash
docker build -t rosweb:humble -f ./Dockerfile-rosweb-humble .
docker run --rm --network host rosweb:humble
```

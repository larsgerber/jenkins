# Jenkins Agent with Docker

## Build

```bash
docker buildx build --platform linux/amd64 -f ./Dockerfile -t docker.larsgerber.ch/jenkins/agent-docker:0.0.0 .
```

## Test

```bash
docker run --rm docker.larsgerber.ch/jenkins/agent-docker:0.0.0 docker --version
```

## Push

```bash
docker push docker.larsgerber.ch/jenkins/agent-docker:0.0.0
```

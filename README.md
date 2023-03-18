# Jenkins

My custom Jenkins server and agent images.

## Agents

See [agents](agents) for more details.

## Server

### Build

```bash
docker buildx build --platform linux/amd64 -f ./Dockerfile -t docker.larsgerber.ch/jenkins/server:0.0.0 .
```

### Push

```bash
docker push docker.larsgerber.ch/jenkins/server:0.0.0
```

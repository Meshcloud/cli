# Meshcloud CLI

Docker build for a container with CLI Tools for OpenStack and Cloud Foundry.
Perfect tool for devops teams that want to keep their workstations pristine and dockerize all the things.

## Usage

Start the container for the first time and attach a shell:
```bash
docker run -it --name meshcloud-cli meshcloud/cli
```

Re-start and attach to an exited instance of the container (the container's file system is preserved):
```bash
docker start -ia meshcloud-cli
```

Get a second shell on the running container:
```bash
docker exec -it meshcloud-cli bash
```

Remove the container:
```bash
docker container rm meshcloud-cli
```




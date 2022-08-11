# Docker-compose for Gitea

## let's run it!

create a hosts entry for `git.petc.com`

```shell
127.0.0.1	git.petc.com
```

bring up the containers!

`docker-compose up --build -d`

let's check it out...

1. Look at Volumes vs the volume from `docker-nginx-sample`

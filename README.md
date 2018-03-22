# hugo-poc
POC using HUGO and Docker

Docs:

https://gohugo.io/getting-started/quick-start/

https://github.com/gohugoio/hugo

## How to exec ##

```
docker-compose up --build
```

## Access virtual container ###
```
$ docker exec -it hugopoc_hugopoc_1 bash
```

### Inside container ### 

```
$ cd quickpock

$ hugo server --baseUrl=hugopoc.local --bind="0.0.0.0"
```


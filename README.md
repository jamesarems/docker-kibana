# Kibana Docker

powered by[![N|Solid](https://jamesnbr.files.wordpress.com/2016/04/jamesnbr.png)](https://nodesource.com/products/nsolid)

Main aim is to ease the complexity to imlement ELK stack.

  - Very Easy to run
  - Destroy and create feature
  - Doest affect your local systems

## New Features!

Still in beta

### Installation

```sh
$ docker pull jamesarems/docker-kibana
$ docker run -d -privileged -p 5601:5601/tcp jamesarems/docker-kibana
```

If you need to change port and run it to default 80, then change the bind port

```sh
$ docker run -d -privileged -p 80:5601/tcp jamesarems/docker-kibana
```

Development going on..Stay tuned

# Kibana

## Description

Extends official Kibana image with disabled x-pack extension plugin.

* Based on: Official `Kibana 5.6.16`

> Note: Provided images require additional configuration for development, staging and production use.

## Tags

| Tag     | Kibana version     | Details     | Dockerfile     |
| :------------- | :------------- | :------------- | :------------- |
| [spryker/kibana:latest](https://hub.docker.com/r/spryker/kibana/tags) | 5.6.16 | [![](https://images.microbadger.com/badges/image/spryker/kibana:latest.svg)](https://microbadger.com/images/spryker/kibana:latest "Get your own image badge on microbadger.com") | [:link:](https://github.com/spryker/docker-kibana/blob/master/5.6.16/Dockerfile) |
| [spryker/kibana:5.6.16](https://hub.docker.com/r/spryker/kibana/tags)  | 5.6.16 | [![](https://images.microbadger.com/badges/image/spryker/kibana:5.6.16.svg)](https://microbadger.com/images/spryker/kibana:5.6.16 "Get your own image badge on microbadger.com") | [:link:](https://github.com/spryker/docker-kibana/blob/master/5.6.16/Dockerfile) |

## How to use

### Pull image
```bash
$ docker pull spryker/kibana:5.6.16
```

### Dockerfile
```dockerfile
FROM spryker/kibana:5.6.16
```

### docker-compose.yml
```yaml
broker:
    image: spryker/kibana:5.6.16
```


## More information
* [Kibana official images](https://github.com/elastic/kibana)

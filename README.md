# Redis image

## Usage

### docker-compose

```yaml
version: '3'

services:
  redis:
    image: 'bjouhaud/redis'
    hostname: 'redis'
    ports:
      - '6379:6379'
    volumes:
      - 'redis:/data'

volumes:
  redis: ~
```

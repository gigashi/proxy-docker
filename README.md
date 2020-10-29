# Proxy Server

+ squid
+ basic authenticate
+ docker-compose

## create user

```bash
docker run --rm -t --entrypoint="htpasswd" httpd:2.4.46-alpine -bn \
user_name \
password \
>> passwords
```

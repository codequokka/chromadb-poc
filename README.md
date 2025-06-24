# chromadb-poc

```console
❯ htpasswd -cb htpasswd admin secret
Adding password for user admin
```

```
❯ curl -u admin:secret http://localhost:8080/api/v2/heartbeat
{"nanosecond heartbeat":1750792542066952505}%
```

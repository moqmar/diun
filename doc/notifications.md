# Notifications

If you choose `webhook` notification, a HTTP request is sent with a JSON format response that looks like:

```json
{
  "diun_version": "0.3.0",
  "status": "new",
  "image": "docker.io/crazymax/swarm-cronjob:0.2.1",
  "mime_type": "application/vnd.docker.distribution.manifest.v2+json",
  "digest": "sha256:5913d4b5e8dc15430c2f47f40e43ab2ca7f2b8df5eee5db4d5c42311e08dfb79",
  "created": "2019-01-24T10:26:49.152006005Z",
  "architecture": "amd64",
  "os": "linux"
}
```

And here is an email sample if you add `mail` notification:

![](../.res/notif-mail.png)

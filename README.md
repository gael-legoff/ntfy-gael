_This is NOT an original piece of work, just a snap of ntfy_

ntfy.sh | Send push notifications to your phone or desktop via PUT/POST

ntfy (pronounced "notify") is a simple HTTP-based pub-sub notification service. With ntfy, you can send notifications to your phone or desktop via scripts from any computer, without having to sign up or pay any fees. If you'd like to run your own instance of the service, you can easily do so since ntfy is open source

**First-time users**

Read the doc at https://docs.ntfy.sh/ on how to get started.

* Configure the server

`sudo vi /var/snap/ntfy-gael/current/server.yml`

```
base-url: "http://ntfy.example.com"
listen-http: :8080
cache-file: "/var/snap/ntfy-gael/common/cache.db"
attachment-cache-dir: "/var/snap/ntfy-gael/common/attachments"
```

* Restart the server

`sudo snap restart ntfy-gael.ntfy-serve`

**2026-02-11**
* v2.17.0 available on amd64 and arm64

**2026-01-24**
* v2.16.0 available on amd64 and arm64

**2025-11-23**
* v2.15.0 available on amd64 and arm64

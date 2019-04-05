# proxy

nginx config to proxy requests to [webtech.union.rpi.edu](https://webtech.union.rpi.edu) to various services. This is designed to be deployed with [dokku](https://github.com/dokku/dokku). It uses an [empty buildpack](https://github.com/wtg/buildpack-empty) since it doesn't actually run any processes.

Right now, it proxies:

- [/](https://webtech.union.rpi.edu) to [WebTech site](https://github.com/wtg/site)
- [/services/identity/](https://webtech.union.rpi.edu/services/identity/) to [Identity](https://github.com/wtg/identity)

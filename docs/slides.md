---
theme: signalwerk
title: coolify
---

```fm
style: negative
background: true
```

## Hello _👋_

# {{process.content.frontmatter.title}}

_eine Open-Source Hosting-Alternative_

<footer>

2024 · DDOS Schaffhausen · Stefan Huber

</footer>

--s--

```fm
style: negative
background: true
```

## Versprechen von coolify (v3)

# Eine _Open-Source_ & <br>**selbsthostbare** <br>Heroku/Netlify-Alternative

--s--

## Warum?

- [Kubernetes](https://kubernetes.io/) oder [Devtron](https://devtron.ai/) sind super, aber komplex
- [Docker](https://www.docker.com/) it's ok... 
- [Heroku](https://www.heroku.com/) ist nice, aber _teuer_ & **Vendor Lock-In**

--s--

## Was ist es

- _Bereitstellung_ von Anwendungen/Diensten **auf einem Server mit Docker**
- Bring your own Server (BYOS) – einfache Installation
- Cloud-Version verfügbar
- Ähnlich wie [CapRover](https://caprover.com/) oder [Kubero](https://www.kubero.dev/)

--s--

```fm
style: negative
background: true
```

## Was?

# Du musst deinen <br>**Web-Service** _hosten_

--s--

## Was du bekommst

- _Server-Hosting_ <small>(Build, Docker, Secrets, …)</small>
- **Datenbank-Hosting** <small>(MariaDB, MongoDB, PostgresSQL, Redis, …)</small>
- _CI_ Integration <small>(gitlab, github)</small>
- Automatische **Routeneinrichtung** <small>([traefik.io](https://traefik.io/))</small>
- Automatische _SSL-Zertifikateinrichtung_ <small>([Let's Encrypt](https://letsencrypt.org/))</small>

--s--

```fm
style: negative
background: true
```

## coolify

# Betrachte es als _Schnellstart_ <br>für **mittelgrosse** Projekte

--s--

## Was du nicht bekommst

- Kein Load Balancing (kein Autoscaling)
- Kein (gutes) Backup out of the box
- Kein tiefgehendes Routing ([traefik](https://traefik.io/) liegt nicht in deiner Hand)

> Version 4 kommt bald – mal sehen

--s--

```fm
style: negative
background: true
```

## mal sehen...

# _Demo_

```
DOMAIN: https://coolify-talk.srv.signalwerk.ch
PORT: 8085
ENV-NAME: TOKEN
```

- [Server](https://github.com/signalwerk/coolify.demo/blob/main/index.js)
- [Dockerfile](https://github.com/signalwerk/coolify.demo/blob/main/Dockerfile)

--s--

```fm
style: negative
background: true
```

## exit 0; thx

# Fragen?

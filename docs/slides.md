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

_the open-source hosting alternative_

<footer>

2023 · Zurich · Stefan Huber

</footer>

--s--

```fm
style: negative
background: true
```

## Claim of coolify (v3)

# An _open-source_ & <br>**self-hostable** <br>Heroku/Netlify alternative

--s--

## Why?

- [Kubernetes](https://kubernetes.io/) or [Devtron](https://devtron.ai/) is great but complex
- [Docker](https://www.docker.com/) is needed (sometimes)
- [Heroku](https://www.heroku.com/) is great but _expensive_ & **vendor lock-in**

--s--

## What is it

- _deploy_ applications/services **to a server with docker**
- Bring your own server (BYOS) – simple installation
- Cloud version available
- Like [CapRover](https://caprover.com/) or [Kubero](https://www.kubero.dev/)

--s--

```fm
style: negative
background: true
```

## Like what?

# You need to _host_ your <br>**web-service**

--s--

## What you get

- _Server hosting_ <small>(Build, Docker, Secrets, …)</small>
- **Database hosting** <small>(MariaDB, MongoDB, PostgresSQL, Redis, …)</small>
- _CI_ integration <small>(gitlab, github)</small>
- Automated **route** setup <small>([traefik.io](https://traefik.io/))</small>
- Automated _SSL certificate_ setup <small>([Let's Encrypt](https://letsencrypt.org/))</small>

--s--

```fm
style: negative
background: true
```

## coolify

# see it as a _quickstart_ <br>for **mid-sized** projects

--s--

## What you don't get

- No load balancing (no Autoscaling)
- No (good) Backup out of the box
- No in depth routing ([traefik](https://traefik.io/) is not in your hand)

> Version 4 soon comming – let's see

--s--

```fm
style: negative
background: true
```

## let's see...

# _Demo_

```
DOMAIN: https://team-talks-test.srv.signalwerk.ch
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

# Questions?

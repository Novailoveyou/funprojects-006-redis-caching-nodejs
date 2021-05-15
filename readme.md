# Redis Caching in Node.js

## About

This is me following Brad Traversy's [youtube video](https://youtu.be/oaJq1mQ3dFI)

Year 2019

## CLI

### To get started

To install Redis on Linux debian

```zsh
sudo apt-get install redis
```

Init package.json

```zsh
npm init -y
```

Install dependencies

```zsh
npm i express node-fetch redis
npm i nodemon -D
```

Run Redis

```zsh
redis-cli
```

### Redis CLI

Set var

```redis
set name nova
```

Get var

```redis
get name
```

Exit

```redis
exit
```

Get rid of cache

```redis
FLUSHALL
```

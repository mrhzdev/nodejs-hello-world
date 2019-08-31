# nodejs-hello-world

This is my sample nodejs dockerized project.

## How to use

```bash
git clone https://github.com/mrhzdev/nodejs-hello-world.git
cd ./nodejs-hello-world
```

### Run `development` env

```bash
docker-compose -f docker-compose.development.yml up --build
```

### Run `test` env

```bash
docker-compose -f docker-compose.test.yml up --build
```

<!-- ### Run `production` env -->
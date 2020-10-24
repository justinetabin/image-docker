# Image Docker
TBD

## Requirements
* Docker v19+

## Workflow

Cloning submodules

```bash
git submodule init
git submodule update
```

Copying Env

```
cp ./envs/your.env ./your-app
```

Build and Run

```bash
docker-compose up -d --build
```
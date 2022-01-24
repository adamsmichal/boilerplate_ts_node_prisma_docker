<div align="center">
  <img width="512" src="https://raw.githubusercontent.com/adamsmichal/boilerplate_ts_node_prisma_docker/main/banner.png" alt="prisma-docker">
</div>

## Setting up a back-end environment for Prisma and Docker

<p align="center">
<img src="https://img.shields.io/github/repo-size/adamsmichal/boilerplate_ts_node_prisma_docker" alt="repo-size-badge">
</p>

Template project to bootstrap a back-end application with nodejs (express), postgresql and prisma within a docker container.

## Getting started
- Clone this repository:
```
git clone https://github.com/adamsmichal/boilerplate_ts_node_prisma_docker.git
```

- Build, fetch and run docker containers
```
docker-compose build
docker-compose up -d postgres
docker-compose run backend npx prisma migrate dev
docker-compose up -d backend
```

- Install dependencies
```
yarn install
```

- Backend works on 5000
<a href="http://localhost:5000/">http://localhost:5000/</a>

- Postgress works on 5432

- You can check your db by prisma studio
```
npx prisma studio
```

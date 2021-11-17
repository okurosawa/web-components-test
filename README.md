# Project setup
## Build image and run docker container
```shell
docker-compose up -d --build
```
## Install node modules
```shell
docker-compose exec app sh
npm i
```
## Start your development
```shell
npm run build
```
## Serve application
```shell
npm run serve
```

## Create Web Components
```shell
vue-cli-service build --target wc --name <file_name> <source_component_path>
```

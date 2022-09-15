# cjoy.io

Personal website build on-top of notion, generated using [loconotion](https://github.com/leoncvlt/loconotion) 

## Build container with loconotion
```
$ docker-compose build loconotion
```
## Run loconotion renderer with any arguments
```
$ docker-compose run loconotion PATH_TO_NOTION_FILE [ARGS]
```
## Example build & run command
```
docker-compose build loconotion && LOCONOTION_LOCAL_DIST=$(pwd)/dist docker-compose run loconotion config/cjoy-io.toml --clean --timeout 10000
```
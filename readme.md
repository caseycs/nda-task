# nda project =)

## Howto

### Run

`docker-compose up`

Open http://docker-machine in browser

### Test

`./vendor/bin/phpunit tests`

## Assumptions/Questions

* There are sometimes legacy percentages in csv, I made extra map to convert them to steps
* Sometimes percentage is missing, I report such cases to logs

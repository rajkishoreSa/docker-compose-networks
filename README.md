# Multi-Container Network Bridging
> NOTE: Creates multiple networks for multiple containers as required. To create a network security between containers, we can create this type of approach.

## Commands to *create* the containers
	docker-compose up -d

## Commands to *delete* the containers
	docker-compose down

## Commands to *stop* the containers
	docker-compose stop

## Commands to *start* the containers
	docker-compose start

## Total *4* Containers
 - nginx
 - httpd (_apache_)
 - adminer
 - mysql

## Total *2* network bridges
 - frontend
 - backend

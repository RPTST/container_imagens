all: create

create:
	docker build -t cticsjeifsc/mediawiki:1.31.12 .
	docker login
	docker push cticsjeifsc/mediawiki:1.31.12
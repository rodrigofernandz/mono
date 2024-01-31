ENV ?= dev

SERVICE=primerB

.PHONY build:
build:
	@echo "Building primerB"

.PHONY push:
push:
	@echo "Pushing primerB"

.PHONY deploy:
deploy:
	@echo "Deploying primerB"
	helm upgrade --install $(SERVICE) ./helm --namespace $(SERVICE) --create-namespace -f ./helm/$(ENV).yaml
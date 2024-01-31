ENV ?= dev

SERVICE=primerA

.PHONY build:
build:
	@echo "Building primerA"

.PHONY push:
push:
	@echo "Pushing primerA"

.PHONY deploy:
deploy:
	@echo "Deploying primerA"
	helm upgrade --install $(SERVICE) ./helm --namespace $(SERVICE) --create-namespace -f ./helm/$(ENV).yaml
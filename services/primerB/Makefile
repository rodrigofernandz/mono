ENV ?= dev
SERVICE=primerB

.PHONY test:
test:
	@echo "Testing primerB"

.PHONY run:
run:
	@echo "Running primerB"

.PHONY build:
build:
	@echo "Building primerB"

.PHONY push:
push:
	@echo "Pushing primerB"

.PHONY deploy: 
deploy: test build push
	@echo "Deploying primerB"
	helm upgrade --install $(SERVICE) ./helm --namespace $(SERVICE) --create-namespace -f ./helm/$(ENV).yaml
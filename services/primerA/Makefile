ENV ?= dev

SERVICE=primerA


.PHONY test:
test:
	@echo "Testing primerA"

.PHONY run:
run:
	@echo "Running primerA"

.PHONY build:
build:
	@echo "Building primerA"

.PHONY push:
push:
	@echo "Pushing primerA"

.PHONY deploy:
deploy: test build push
	@echo "Deploying primerA"
	helm upgrade --install $(SERVICE) ./helm --namespace $(SERVICE) --create-namespace -f ./helm/$(ENV).yaml
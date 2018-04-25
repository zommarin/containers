

.PHONY: login
login:
	docker login -u zommarin

.PHONY: build
build:
	docker build -t zommarin/ubuntu-util .

.PHONE: push
push: build
	docker push zommarin/ubuntu-util

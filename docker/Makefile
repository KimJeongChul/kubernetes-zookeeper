VERSION=3.7.0
PROJECT=kimjeongchul

all: build

build:
	docker build --pull -t ${PROJECT}/kubernetes-zookeeper:${VERSION} .

push: build
	docker -- push ${PROJECT}/kubernetes-zookeeper:${VERSION}

.PHONY: all build push

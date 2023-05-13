include ../VERSIONS

IMAGE=database-backup
VERSION=0.0.0
TAG=$(IMAGE):$(VERSION)

build:
	DOCKER_BUILDKIT=1 docker buildx build \
	--build-arg ALPINE_VERSION=$(ALPINE_VERSION) \
	-t $(TAG) -f ./Dockerfile .

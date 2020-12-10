NAME   := korutx/typescript
TAG    := alpine
IMG    := ${NAME}:${TAG}
LATEST := ${NAME}:latest

build-docker:
        docker build -t ${IMG} .
        docker tag ${IMG} ${LATEST}

push:
        @docker push ${NAME}

login:
        @docker login -u ${DOCKER_USER} -p ${DOCKER_PASS}


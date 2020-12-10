NAME   := korutx/typescript
TAG    := semver-alpine
IMG    := ${NAME}:${TAG}

build-docker:
        docker build -t ${IMG} .

push:
        @docker push ${NAME}

login:
        @docker login -u ${DOCKER_USER} -p ${DOCKER_PASS}


FROM korutx/typescript:alpine

RUN  apk add --no-cache --update git openssh bash gawk \
    && git clone https://github.com/korutx/git-semver.git \
    && git-semver/install.sh

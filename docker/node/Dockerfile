FROM node:9.3.0-alpine

ARG GID=1000
ARG UID=1000

RUN apk add --no-cache bash shadow

RUN groupmod -g $GID node && \
    usermod -g $GID -u $UID node

ADD remote-call-editor /usr/bin/remote-call-editor

ENV REACT_EDITOR=remote-call-editor

RUN npm install -g create-react-native-app

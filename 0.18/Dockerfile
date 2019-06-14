FROM node:8

MAINTAINER pastelInc <keyaki765@gmail.com>

RUN npm install -g elm@0.18 elm-test@0.18 --no-progress --unsafe-perm=true --allow-root

ENTRYPOINT ["elm-test"]
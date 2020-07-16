FROM node:10

MAINTAINER pastelInc <keyaki765@gmail.com>

RUN npm install -g elm@latest-0.18.0 elm-test@latest-0.18.0 --no-progress --unsafe-perm=true --allow-root

ENTRYPOINT ["elm-test"]
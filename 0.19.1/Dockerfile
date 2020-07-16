FROM node:10

MAINTAINER pastelInc <keyaki765@gmail.com>

RUN npm install -g elm@latest-0.19.1 elm-test@latest-0.19.1 --no-progress --unsafe-perm=true --allow-root

ENTRYPOINT ["elm-test"]
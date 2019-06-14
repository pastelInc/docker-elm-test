FROM node:8

MAINTAINER pastelInc <keyaki765@gmail.com>

RUN npm install -g elm@elm0.19.0 elm-test@elm0.19.0 --no-progress --unsafe-perm=true --allow-root

ENTRYPOINT ["elm-test"]
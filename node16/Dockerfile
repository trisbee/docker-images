FROM node:16.13.2-alpine

# add packages to system
RUN apk update
RUN apk add rsync

# Corepack is included by default with all Node.js installs, but is currently opt-in.
RUN corepack enable
RUN yarn set version stable

CMD [""]

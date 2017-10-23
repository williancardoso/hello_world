FROM mhart/alpine-node:6.10

ENV APP_HOME /hello-world

# Install Modules:
WORKDIR   $APP_HOME

# Copy in files:
COPY      . $APP_HOME

EXPOSE    80
CMD       ["node", "index.js"]

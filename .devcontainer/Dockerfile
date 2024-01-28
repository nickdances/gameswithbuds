# Current Node LTS as of 1/2024
FROM node:20-alpine3.18

RUN apk add git openssh-client

# Install AWS CDK globally.
RUN npm install -g aws-cdk-lib typescript

# Start a bash shell when the container starts.
CMD [ "bash" ]
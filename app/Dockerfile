FROM node:14

WORKDIR /home/node

ARG NODE_ENV
ENV NODE_ENV $NODE_ENV

# COPY package.json /home/node
# COPY package-lock.json /home/node
COPY app /home/node
RUN npm ci --prod

# USER node
# COPY . /home/node



# replace this with your application's default port
EXPOSE 3000

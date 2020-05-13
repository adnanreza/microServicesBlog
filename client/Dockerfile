FROM node:alpine

# This is used to run creat-react-app in a docker container
ENV CI=true

WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]

FROM node:11
WORKDIR /app/Frontend/client
COPY package.json /app/Frontend/client
RUN npm install
RUN npm build
COPY . .
CMD ["npm", "run", "dev"]
FROM node:alpine
WORKDIR "/app"
COPY ./packaage*.json ./
RUN npm install 
COPY . . 
CMD ["npm", "run", "start"]
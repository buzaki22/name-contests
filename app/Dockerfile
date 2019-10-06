FROM node:10.15.0-alpine
EXPOSE 3000

WORKDIR /home/app
COPY package.json /home/app/
RUN npm install 
COPY . /home/app
CMD [ "yarn", "start" ]

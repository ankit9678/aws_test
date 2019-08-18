FROM node
WORKDIR /client
COPY package.json /client
RUN npm install
COPY . /client
RUN npm run build
CMD npm run start
EXPOSE 3000
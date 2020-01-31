FROM node:13.7.0-alpine3.10
RUN mkdir /frontend
WORKDIR /frontend
ENV PATH /frontend/node_modules/.bin:$PATH
COPY package.json /frontend/package.json
RUN npm install --silent
RUN npm install react-scripts@3.0.1 -g --silent
EXPOSE 3000:3000
CMD ["npm", "start"]

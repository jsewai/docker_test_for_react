FROM node:13.7.0-alpine3.10
RUN mkdir /frontend
WORKDIR /frontend
ENV PATH /frontend/node_modules/.bin:$PATH
COPY ./ /frontend
CMD npm start

FROM node:16.18

WORKDIR /frontend-react-js
ENV PORT 3000

COPY . /frontend-react-js

RUN npm install
EXPOSE ${PORT}
CMD [ "npm", "start" ]
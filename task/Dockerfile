FROM node
COPY ./taskserver /taskserver
WORKDIR /taskserver
RUN npm install
EXPOSE 8000
CMD ["node","server.js"]

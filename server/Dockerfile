FROM node
RUN mkdir /app
WORKDIR /app
ADD . /app
RUN npm install
EXPOSE 3000
CMD ["npm", "run", "start"]
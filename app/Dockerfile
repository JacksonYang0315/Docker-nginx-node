FROM node
RUN mkdir /website 
WORKDIR /website 
ADD . /website
RUN npm install
EXPOSE 3000
CMD ["npm", "run", "start"]
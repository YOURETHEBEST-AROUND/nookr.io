FROM node:alpine
COPY . /srv
WORKDIR /srv
RUN npm install --production
CMD ["node", "app.js"]
FROM node:latest
WORKDIR /usr/src/frontend
COPY package.json package-lock.json .
RUN npm install
RUN npm install -g next
COPY . .
EXPOSE 3000
CMD ["npm", "run", "dev"] 
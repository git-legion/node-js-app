FROM node:latest
WORKDIR /app
COPY package*.json /app/
RUN npm install 
copy . .
EXPOSE 5000
CMD ["npm", "start"]




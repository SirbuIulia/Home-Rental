# Backend Dockerfile

# Use Node.js image from DockerHub
FROM node:16

# Create app directory
WORKDIR /usr/src/app

# Copy package.json and install dependencies
COPY package*.json ./

RUN npm install

# Expose the port that your application runs on
EXPOSE 3001
# Copy the rest of the backend code
COPY . .

CMD ["npm", "run", "start"]
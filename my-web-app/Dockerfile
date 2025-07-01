FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --production
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
# This Dockerfile sets up a Node.js application in a lightweight Alpine Linux container.
# It installs only production dependencies and exposes port 3000 for the application.
# The application can be started with the command `npm start`.
# Ensure that your application listens on port 3000 in your code.               
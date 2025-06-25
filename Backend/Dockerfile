# Base image
FROM node:14

# Set working directory
WORKDIR /usr/src/app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy source code
COPY . .

# Expose the required port
EXPOSE 3000

# Start the application
CMD ["node", "server.js"]


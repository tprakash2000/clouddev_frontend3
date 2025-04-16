# Use a Node.js base image
FROM node:18

# Set working directory
WORKDIR /usr/src/app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the entire project
COPY . .

# Expose the app's port
EXPOSE 3000

# Run the app
CMD ["npm", "start"]

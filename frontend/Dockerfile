# Use official Node.js image
FROM node:16

# Set the working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the app's source code
COPY . .

# Expose the port your frontend will use
EXPOSE 3000

# Start the frontend with `npm start`
CMD ["npm", "start"]
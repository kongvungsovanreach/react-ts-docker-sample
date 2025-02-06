# Use official Node.js image
FROM node:16

# Set the working directory
WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the app's source code
COPY . .

# Expose the port your backend listens on
EXPOSE 5000

# Start the backend with `npm run dev`
CMD ["npm", "run", "dev"]
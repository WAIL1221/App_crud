FROM node:16

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY ./package*.json ./

# Install app dependencies
RUN npm install

# Bundle app source
COPY . ./

# Expose port
EXPOSE 8080

# Start command
CMD ["npm", "run", "serve"]

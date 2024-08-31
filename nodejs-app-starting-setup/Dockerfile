FROM node

# Create app directory
WORKDIR /app

# Install app dependencies
COPY . /app

# Bundle app source
RUN npm install

# Bind the port that the image will run on
EXPOSE 80

# Define the Docker image's behavior at runtime
CMD ["node", "server.js"]
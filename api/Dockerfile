# Node Image
FROM node:14-alpine

# Create app directory
WORKDIR /usr/src/app

# Copy package.json file
COPY package*.json ./

# Install node depandancies
RUN npm install

# Copy app source code
COPY . .

# Expose port
EXPOSE 5000

# Run app
CMD [ "npm", "run", "dev" ]
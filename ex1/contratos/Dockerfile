FROM node
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
COPY package*.json ./
RUN npm install mongoose
RUN npm install

# Copy app source code
COPY . .
#Expose port and start application
EXPOSE 16000
CMD [ "npm", "start" ]
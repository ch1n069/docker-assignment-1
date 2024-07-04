FROM node

# declare the working directory
WORKDIR /app

# copy the package.json 
COPY package.json /app

# install the node modules
RUN npm install

# copy all the files into the app folder
 COPY . /app

# Declare the port to be used this is for documentation purposes only
EXPOSE 3000


# commands to run the server
CMD [ "node","server.js" ]
FROM node:alpine

# Create app directory
WORKDIR SCA-Cloud-Project/

# Bundle app source
COPY . .

# Edit content of app.js
RUN sed -i 's/Welcome to SCA Cloud School Application/Welcome to SCA Cloud School Application, this is my first assessment/' app.js

# Opens port 3030
EXPOSE 3030

# Runs the command "node app.js"
CMD [ "node", "app.js" ]

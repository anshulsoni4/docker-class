#  as we are going to run a JS file we need to add node runtime from docker hub. 
FROM node:20-alpine

# now we set the working directory, where codes will be run.
WORKDIR /app 

#  now we copy the files from our dir to docker 
COPY . .

# now we specify the command to run the app
CMD node hello.js
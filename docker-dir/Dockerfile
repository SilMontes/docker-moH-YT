# images -> we can view them on the documentation
# alpine using linux distribution and it is a very small image
FROM node:alpine 

# copy the files to be used. Into the image there is a file system, into that file system we will create a directory call app

COPY . /app

# execute a command

#CMD node /app/app.js   -> if we do not use WORKDIR /app  in this case, we will have to use /app before the file name
WORKDIR /app
CMD node app.js
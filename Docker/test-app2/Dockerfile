# Initalizing the image with version

FROM node:20

# Creating a Working Directory
WORKDIR /app

# Copying the file to the app directory

COPY . .

# Running npm install Command

RUN npm install

#Exposing the PORT number
EXPOSE 3000

# Running npm start in the terminal for output
CMD [ "npm","start" ]



# Used Following Commands for required output


# docker build . to build the docker file 
# docker run -d -p 3000:3000 image_id -d for detach mode and -p for port binding
# docker stop image_id to stop the container

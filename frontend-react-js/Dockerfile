#Reference node image
FROM node:16.18

#INSIDE container
#Set Environment Variables
ENV PORT=3000

#Copy from OUTSIDE the container to INSIDE the container
COPY . /frontend-react-js

#Create a new folder INSIDE the container
WORKDIR /frontend-react-js

#INSIDE the container
#Install the npm libraries used for the app
RUN npm install

EXPOSE ${PORT}

#Command
CMD ["npm","start"]

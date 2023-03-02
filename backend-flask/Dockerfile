#Reference python image
FROM python:3.10-slim-buster

#Create a new folder INSIDE the container
WORKDIR /backend-flask

#Copy from OUTSIDE the container to INSIDE the container
#This contains the libraries want to install to run the app
COPY requirements.txt requirements.txt

#INSIDE the container
#Install the python libraries used for the app
RUN pip3 install -r requirements.txt

#Copy from OUTSIDE the container to INSIDE the container
# . means everything in the current directory
# first period . - /backend-flask (outside the container)
# second period . - /backend-flask (outside the container)
COPY . .

#INSIDE container
#Set Environment Variables (env vars), will remain set when the container is running
ENV FLASK_ENV=development

EXPOSE ${PORT}

#CMD (Command), command to run flask
#-m means module
#host 0.0.0.0 means localhost
#python3 -m flask run --host=0.0.0.0 --port=4567
CMD [ "python3" , "-m" , "flask" , "run" , "--host=0.0.0.0" , "--port=4567"]

#Follow guide from MSLEARN and Cantril


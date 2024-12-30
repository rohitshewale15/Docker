FROM python:3.8-alpine

     
     COPY ./requirements.txt /app/requirements.txt 
     # copy the requirement file into the image 
     
     WORKDIR /app  
     # switch working directory
     
     RUN pip install -r requirements.txt
     # install the dependencies and packages in the requirements file
     
     COPY . /app
     # copy every content from the local file to the image
     
     ENTRYPOINT [ "python" ]
     # configure the container to run in an executed manner
     
     CMD ["app.py" ]

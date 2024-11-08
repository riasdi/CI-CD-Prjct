# The base image
FROM python:3.8

# Creating a work directory app
WORKDIR /app

#copy requirement file
COPY requirements.txt. 

#Install dependency
RUN pip install -r requirements.txt

#Copying app code into a directory
COPY . .

EXPOSE 5000

CMD ["python", "app.py"]

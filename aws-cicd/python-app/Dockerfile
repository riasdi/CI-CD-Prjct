# The base image
FROM python: 3.8

#creating a work directory app
WORKDIR /app

#copy requirement file
COPY requirements.txt. 

#Install dependency
RUN pip install -r requirements.txt

#Copying app code into directory
COPY . .

EXPOSE 5000

CMD ["python", "app.py"]

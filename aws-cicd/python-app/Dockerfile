# The base image
FROM python:3.8

# Creating a work directory app
WORKDIR /app

# Copy requirement file
COPY requirements.txt /app

#Install dependency
RUN pip install -r requirements.txt

# Copy the rest of the application code
COPY . /app

EXPOSE 5000

CMD ["python", "app.py"]

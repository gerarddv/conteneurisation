# Use official python runtime base image

# Set the container application directory to /app

# Add requirements.txt to container folder /app/requirements.txt 

# Execute pip install -r requirements.txt

# Copy our code from the current folder to /app inside the container

# Make port 80 available for links and/or publish

# Define the command to be run when launching the container : `python app.py`

# Use official Python runtime base image
FROM python:latest

# Set the working directory inside the container
WORKDIR /app

# Copy the requirements file to the container
COPY requirements.txt /app/

# Install Python dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the application code to the container
COPY . /app/

# Expose port 80 for the application
EXPOSE 80

# Define the command to run the application
CMD ["python", "/app/app.py"]


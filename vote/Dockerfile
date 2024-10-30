# Use official python runtime base image

# Set the container application directory to /app

# Add requirements.txt to container folder /app/requirements.txt 

# Execute pip install -r requirements.txt

# Copy our code from the current folder to /app inside the container

# Make port 80 available for links and/or publish

# Define the command to be run when launching the container : `python app.py`




# Use official python runtime base image
FROM python:latest

# Set the container application directory to /app
WORKDIR /app

# Add requirements.txt to container folder /app/requirements.txt
COPY requirements.txt .

# Execute pip install -r requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy our code from the current folder to /app inside the container
COPY . .

#Make port 80 available for links and/or publish
EXPOSE 80

# Define the command to be run when launching the container
CMD ["python", "app.py"] #Use official python runtime base image
FROM python:latest

# Set the container application directory to /app
WORKDIR /app

# Add requirements.txt to container folder /app/requirements.txt
COPY requirements.txt .

# Execute pip install -r requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy our code from the current folder to /app inside the container
COPY . .

#Make port 80 available for links and/or publish
EXPOSE 80

#Define the command to be run when launching the container
CMD ["python", "app.py"]
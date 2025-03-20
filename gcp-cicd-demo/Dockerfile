# Use official Python runtime as base
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy the application code
COPY . /app

# Install dependencies
RUN pip install flask

# Define the command to run the app
CMD ["python", "main.py"]

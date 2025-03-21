# Use an official Python runtime as a base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the application files into the container
COPY app.py .

# Install required dependencies
RUN pip install flask

# Expose port 5000
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]


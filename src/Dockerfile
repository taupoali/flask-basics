# Dockerfile
FROM python:3.13-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the application code into the container
COPY . /app

# Install dependencies
RUN pip install -r requirements.txt

# Expose the port the app will run on
EXPOSE 8080

# Command to run the app
CMD ["python", "app.py"]

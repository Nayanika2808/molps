# Use Python base image
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy the project files to the container
COPY . /app

# Install dependencies (pytest for testing)
RUN pip install pytest

# Run the tests as the default command
CMD ["pytest"]

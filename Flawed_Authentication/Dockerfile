# Use an official Python image as base
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy application files to the container
COPY . .

# Install required dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Expose the port Flask runs on
EXPOSE 5000

# Run the Flask app
CMD ["python", "app.py"]

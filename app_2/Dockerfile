# Use official Python image
FROM python:3.10-slim

# Set working directory
WORKDIR /app

# Copy app files
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY app.py .

# Expose the port
EXPOSE 5000

# Run the app
CMD ["python", "app.py"]
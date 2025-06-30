# Use a lightweight base image
FROM python:3.10-slim

# Set the working directory
WORKDIR /app

# Copy dependencies
COPY requirements.txt .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy app code
COPY . .

# Expose the Flask port
EXPOSE 5001

# Run the app
CMD ["python", "app.py"]
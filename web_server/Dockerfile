# Use a lightweight base image
FROM python:3.10-slim

# Set work directory
WORKDIR /app

# Copy project files
COPY . .

# Install dependencies
RUN pip install --no-cache-dir -r requirments.txt

# Expose port 8001
EXPOSE 8001

# Run the app
CMD ["fastapi", "dev", "main.py"]

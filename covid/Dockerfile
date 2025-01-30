
FROM python:3.12.8

WORKDIR /app

# Copy requirement files
COPY requirements.txt /app/

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the entire project
COPY . /app/

# Expose port
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]
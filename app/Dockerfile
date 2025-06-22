# Use slim base image
FROM python:3.11-slim

# Create non-root user
RUN useradd -m appuser

# Set working directory
WORKDIR /home/appuser

# Copy necessary files
COPY app.py requirements.txt ./

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Set permissions and switch to non-root
RUN chown -R appuser:appuser /home/appuser
USER appuser

# Expose application port
EXPOSE 5000

# Command to run the app
CMD ["python3", "app.py"]

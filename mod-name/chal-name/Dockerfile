# Use an official lightweight Python image
FROM python:3.11-slim

# Set working directory
WORKDIR /challenge

# Copy required files into the container (or all files)
COPY . /challenge

# Install PyYAML (and any other dependencies if needed)
RUN pip install --no-cache-dir -r requirements.txt

# Run your script
CMD ["python", "/challenge/grep_template.py", "/challenge/input.yml"]
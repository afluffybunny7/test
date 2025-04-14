# Use an official lightweight Python image
FROM python:3.11-slim

# Set working directory
WORKDIR /challenge

# Copy required files into the container
COPY grep_template.py input.yml run.py /challenge/

# Install PyYAML
RUN pip install --no-cache-dir pyyaml

# Run your script
CMD ["python", "/challenge/run.py"]
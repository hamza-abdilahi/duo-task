# Use Python 3.6 or later as a base image
FROM python:3.6
# Copy contents into image
COPY requirements.txt .
COPY app.py .
# Install pip dependencies from requirements
RUN pip install -r requirements.txt
# Set YOUR_NAME environment variable
ENV YOUR_NAME Hamza
# Expose the correct port
EXPOSE 5500
# Create an entrypoint
ENTRYPOINT  ["python", "app.py"]

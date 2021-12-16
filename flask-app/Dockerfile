#Use Python 3.6 as a base image

# Copy contents into image
 
# install pip dependencies from requirements file
 
# Expose correct port

# Create an entrypoint

# Use Python 3.6 or later as a base image
FROM python:3.7
# Copy contents into image
WORKDIR /app
COPY . .
# Install pip dependencies from requirements
RUN pip install -r requirements.txt
# Set YOUR_NAME environment variable
ENV YOUR_NAME=SOME_NAME
# Expose the correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT ["python", "app.py"]
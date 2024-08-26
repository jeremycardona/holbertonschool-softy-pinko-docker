# getting latest unbuntu version
FROM ubuntu:latest

# getting apt index update
RUN apt-get update -y
RUN apt-get install -y python3 python3-pip

# Install Flask using pip3
RUN pip3 install flask --break-system-packages
# Install flask cors
RUN pip3 install flask-cors --break-system-packages
# Set working directory
WORKDIR /app

# Copy Python file to container
COPY ./api.py /app/api.py

EXPOSE 5252

# Define command to run the package
CMD [ "python3", "api.py" ]
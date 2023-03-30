# Base image
FROM python:3.6

EXPOSE 3001
# Set working directory
WORKDIR /app

COPY . /app

COPY requrements.txt /app
RUN pip install -r requrements.txt



# Set command to run the application
CMD python front.py




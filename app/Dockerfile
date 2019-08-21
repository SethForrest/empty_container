# Define what enviroment you want
FROM python:3.7

# working directory
WORKDIR /app

# copies top level stuff into working directory
COPY . /app

# Install requirements
RUN pip install -r requirements.txt

# Run the program
CMD ["python", "myApp.py"]

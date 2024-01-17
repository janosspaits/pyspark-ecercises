FROM my-python-java-base:latest

# Set the working directory in the container
WORKDIR /app

# Copy the requirements file into the container at /app
COPY requirements.txt /app/

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy the local directory contents into the container at /app
COPY . /app

# No need to expose ports since we're not starting a server
# No need to define a command since we'll be using this for interactive work

# Start from ubuntu image
FROM ubuntu:20.04

# Use /Users/user/app as our workdir
WORKDIR /Users/alexho/Exercise-1.8

# Copy the script.sh file from this location to /Users/user/app
COPY script.sh . 

# Installation of curl 
RUN apt-get update 

RUN apt-get install -y curl

RUN chmod +x script.sh

# Running the script commands

CMD ./script.sh
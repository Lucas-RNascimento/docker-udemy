# Start your image with a base image - Very 1st Command in the docker
FROM image

# Install any software, create dir
RUN command

# Set the JDK path | We can give equal or just space np
ENV environment_variable=environment_valua

# The /app directory should act as the main application direcotory where all the 
WORKDIR directory

# Here adding file into host location to be copied into container location
ADD host_file container_file

# Run any Command after Container is created frin this image*
ENTRYPOINT command_to_be_executed

# Expose any port ro execute container/Application
EXPOSE port_number

# Run Any Command after Container is created from this image*
EBTRYPOINT command_to_be_execute




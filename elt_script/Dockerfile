# FROM faisaltareque/python-postgre:v1
# FROM ubuntu:20.04
# FROM python:3.9
FROM postgres:latest

# Install PostgreSQL command-line tools
# RUN apt update --allow-insecure-repositories
# RUN apt update -y
RUN apt-get update -y
RUN apt-get install -y python3
# # Copy the ELT script 
COPY . .

# # Set the default command to run thea ELT script
CMD ["python3", "elt_script.py"]
# CMD ["sleep", "infinity"]

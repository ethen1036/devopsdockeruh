#Fetching required image
FROM ubuntu:20.04

#Setting up work directory
WORKDIR usr/src/app
 
#Instruction to install curl
RUN apt update && apt install curl -y

#Copy script
COPY script.sh .

#Command to run the script
CMD ./script.sh

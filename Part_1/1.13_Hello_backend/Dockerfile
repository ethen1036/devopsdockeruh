#Obtain required OS image
FROM golang:1.16

#Working directory as per convention
WORKDIR /usr/src/app

#Exposing port as per requirement
EXPOSE 8080

#Copy source code
COPY . .

#Create a build as per README
RUN go build

#Test project
RUN go test

#Execute project
CMD ./server 

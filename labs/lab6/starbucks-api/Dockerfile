FROM golang:1.11 
EXPOSE 3000
RUN mkdir /app 
ADD . /app/ 
WORKDIR /app 
ENV GOPATH /app
RUN cd /app ; go install starbucks
CMD ["/app/bin/starbucks"]

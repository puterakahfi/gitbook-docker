FROM phusion/baseimage:latest



RUN  curl -sL https://deb.nodesource.com/setup_7.x | bash && \
     apt-get update && \
     apt-get install -y nodejs && \
     npm install gitbook-cli -g
 
CMD ["gitbook-editor"]

FROM node:14

WORKDIR /

COPY . /
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash && apt install -y nodejs && npm install
EXPOSE 8000
COPY . / 
CMD [ "npm", "start" ]
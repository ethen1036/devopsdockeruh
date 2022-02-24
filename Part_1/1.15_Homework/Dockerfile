FROM ubuntu

WORKDIR usr/src/app

EXPOSE 3000

RUN apt update && apt install -y curl

RUN curl -fsSL https://deb.nodesource.com/setup_lts.x | bash -

RUN apt install -y nodejs

COPY ./dcreact/ .

RUN npm install

CMD npm start

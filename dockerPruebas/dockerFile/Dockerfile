FROM ubuntu:lunar-20221216

RUN apt-get update && apt-get install -y locales

RUN apt install nodejs

RUN nodejs -v
RUN npm -v

RUN cd Desktop

RUN mkdir APP

WORKDIR Desktop/APP/

COPY . .

CMD ["node","/APP/src/index.js"]

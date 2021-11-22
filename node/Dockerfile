FROM node:14

ENV TZ=Asia/Shanghai

COPY ./sources.list /etc/apt/sources.list

RUN apt-get update && apt-get install -y -f --allow-downgrades \
	sudo \
        git \
        zip \
        supervisor \
        procps \
	net-tools \
	curl \
	wget \
        cron

RUN npm install -g pm2


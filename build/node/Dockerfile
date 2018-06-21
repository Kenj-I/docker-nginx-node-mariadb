FROM node:6-alpine

WORKDIR /usr/src/app

# タイムゾーンの変更
ENV TZ Asia/Tokyo
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

# 言語設定
# RUN apt-get install -y locales
# RUN locale-gen ja_JP.UTF-8
# RUN apt-get install -y task-japanese
# RUN locale-gen en_US.UTF-8
# ENV LANG=C.UTF-8
# ENV LANGUAGE=en_US:en

# npm version up
# RUN npm i -g npm

# vue-cli
RUN npm install -g vue-cli

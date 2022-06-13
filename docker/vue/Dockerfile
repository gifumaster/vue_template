FROM node:18-buster-slim
RUN npm install --global @vue/cli
RUN apt update \
    && apt install -y git

WORKDIR /projects


# 日本語設定
ENV LANG=C.UTF-8
ENV LANGUAGE=en_US:
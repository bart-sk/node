FROM node:10.13.0-stretch
LABEL maintainer="opensource@programator.sk"
RUN  apt-get update && \
     apt-get --yes install openssh-client && \
     apt-get --yes install git && \
     npm i -g yarn && \ 
     mkdir -p ~/.ssh && \
     chmod 700 ~/.ssh && \
     echo -e "Host *\n\tStrictHostKeyChecking no\n\n" > ~/.ssh/config
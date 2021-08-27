


# 1. node 설치

FROM node:12   
# FROM ubuntu:20.04
# RUN apt-get update
# RUN DEBIAN_FRONTEND=noninteractive apt-get install -y nodejs npm


# 2. 패키지 우선 복사
# COPY ./package* /usr/src/app/ 
# WORKDIR /usr/src/app 
# RUN npm install

# 2. 소스 복사
COPY . /usr/src/app

# 3. Nodejs 패키지 설치
WORKDIR /usr/src/app
RUN npm install

# 4. WEB 서버 실행 (Listen 포트 정의 )
EXPOSE 3000
CMD node app.js



# kubectl get portal -n portal
# kubectl delete po app -n service
# docker run -it -d -p 8000:80  -- rm ubuntu:latest bash 
#
#
#
#
#
#

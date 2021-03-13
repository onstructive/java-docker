FROM adoptopenjdk:${IMAGE_TAG}
MAINTAINER silvio.wangler@onstructive.ch

ENV TZ=Europe/Zurich
RUN apt update && apt upgrade -y && apt install -y curl fontconfig libfreetype6 && rm -rf /var/lib/apt/lists/** && ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

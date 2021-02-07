FROM openjdk:${IMAGE_TAG}
MAINTAINER silvio.wangler@onstructive.ch

ENV TZ=Europe/Zurich
RUN apt update && apt install -y curl && rm -rf /var/lib/apt/lists/** && ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

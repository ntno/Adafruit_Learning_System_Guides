FROM alpine:3.10.3
RUN apk add  --no-cache ffmpeg bash curl wget 
RUN echo 'alias ffmpeg="ffmpeg -hide_banner"' >> ~/.bashrc
WORKDIR /usr/src
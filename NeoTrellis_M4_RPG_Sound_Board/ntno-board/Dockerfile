FROM alpine:3.10.3
RUN apk add  --no-cache ffmpeg bash curl wget 
RUN echo 'alias ffmpeg="ffmpeg -hide_banner"' >> ~/.bashrc
WORKDIR /usr/src
COPY samples samples
COPY code.py code.py
COPY color_names.py color_names.py
COPY notes.txt notes.txt
COPY soundboard.txt soundboard.txt


FROM alpine:3.10.3
RUN apk add  --no-cache ffmpeg bash curl wget 
WORKDIR /usr/src
# COPY new-mp3s new-mp3s
# COPY new-wavs new-wavs
# COPY min-wavs min-wavs
COPY samples samples
COPY code.py code.py
COPY color_names.py color_names.py
COPY notes.txt notes.txt
COPY soundboard.txt soundboard.txt



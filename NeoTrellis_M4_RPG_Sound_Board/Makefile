cwd  := $(shell pwd)

build:
	docker build ntno-board -t ntno-board:latest
run: build
	docker run -it \
	--mount type=bind,source="$(cwd)",target=/usr/src \
	ntno-board:latest /bin/bash
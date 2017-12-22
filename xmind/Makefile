include ../shared/Makefile.vars
TAG := "mdwheele/xmind:latest"
include ../shared/Makefile

.PHONY: xmind

xmind:
	docker run -it -e DISPLAY=unix${DISPLAY} \
	        -v /tmp/.X11-unix:/tmp/.X11-unix \
	        mdwheele/xmind:latest

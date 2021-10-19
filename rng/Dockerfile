FROM 	python:alpine
MAINTAINER      brahim.hamdi.consult@gmail.com
RUN 	pip install Flask
RUN 	apk add --update build-base curl
COPY 	rng.py /
EXPOSE 	80
CMD 	["python", "rng.py"]


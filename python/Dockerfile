FROM python:3.8-slim-buster

RUN apt update && apt install -y build-essential

RUN apt install --fix-missing -y libpq-dev vim gawk jq telnet openssl \
	    iputils-ping dnsutils curl wget gnupg socat bash procps python2 \
	    postgresql-client cargo libffi-dev

ENTRYPOINT []

FROM ubuntu

LABEL maintainer "Kartikey Sharma <kartikey.sharma34@yahoo.com>"

RUN apt-get update && apt-get install -y \
	traceroute \
	--no-install-recommends \
	&& rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["traceroute"]

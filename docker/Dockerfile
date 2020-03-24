FROM ubuntu:latest

RUN apt-get update && \
    apt-get install --no-install-recommends -y python3-numba \
	python3-sympy python3-scipy python3-pandas && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "/usr/bin/python3" ]

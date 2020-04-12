FROM ubuntu:latest

RUN apt-get update && \
    apt-get install --no-install-recommends -y libopenblas-base \
	python3-pip python3-setuptools && \
    pip3 install --no-cache-dir --compile numba scipy pandas sympy h5py && \
    rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "/usr/bin/python3" ]

FROM python:3.3
MAINTAINER Tobias Kölling <tobias.koelling@physik.uni-muenchen.de>
RUN apt-get update && apt-get -y install \
    liblapack-dev \
    libatlas-dev \
    gfortran
RUN pip install --no-cache-dir \
    numpy \
    scipy \
    sympy \
    matplotlib

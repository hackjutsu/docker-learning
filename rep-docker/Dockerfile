FROM ubuntu:14.04
MAINTAINER Di Chen <chenditc@gmail.com>
RUN apt-get update && apt-get install -y build-essential \
                                         g++ \
                                         gfortran \
                                         ipython \
                                         ipython-notebook \
                                         libatlas3gf-base \
                                         libatlas-dev \
                                         libblas-dev \
                                         libfreetype6-dev \
                                         libjpeg8-dev \
                                         liblapack-dev \
                                         libpng-dev \
                                         libxft-dev \
                                         python3-dev \
                                         python3-matplotlib \
                                         python3-numpy \
                                         python3-pip \
                                         python3-scipy \
                                         python3-setuptools \
                                         python3-nose \
                                         python3-pandas \
                                         python-sympy
RUN pip3 install --upgrade pip3 && pip3 install -r https://raw.githubusercontent.com/chenditc/docker-learning/master/rep-requirement.txt

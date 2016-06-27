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
                                         libffi-dev \
                                         libjpeg8-dev \
                                         liblapack-dev \
                                         libncurses5-dev \
                                         libpng-dev \
                                         libssl-dev \
                                         libxft-dev \
                                         python-dev \
                                         python-matplotlib \
                                         python-numpy \
                                         python-pip \
                                         python-scipy \
                                         python-setuptools \
                                         python-nose \
                                         python-pandas \
                                         python-sympy
RUN pip install -r https://raw.githubusercontent.com/chenditc/docker-learning/master/rep-docker/rep-requirement.txt
RUN pip install --pre xgboost
RUN pip install rep --no-dependencies

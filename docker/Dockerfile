FROM ubuntu:latest

RUN apt-get update \
  && apt-get install -y python python-pip \
  && pip install --upgrade pip

RUN apt-get install -y git curl zip unzip

RUN pip install scipy sklearn tensorflow tqdm

RUN pip install matplotlib
#------------------------------------------------------------------------------

# RUN mkdir /JaeD42 && \
# cd /JaeD42 && \
# git clone https://github.com/JaeD42/CUNOCR.git && \
# cd ./CUNOCR

# #
# WORKDIR /brendenlake/
# RUN cd /brendenlake && git clone https://github.com/brendenlake/omniglot.git

# LABEL maintainer_dockerfile="haisam.ido@gmail.com"
# LABEL maintainer_code=https://github.com:JaeD42/CUNOCR


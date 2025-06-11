FROM ubuntu:22.04

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
  build-essential \
  cmake \
  git \
  libgtk-3-dev \
  libnss3 \
  libxss1 \
  libasound2 \
  libxcomposite-dev \
  libxrandr-dev \
  libxdamage-dev \
  libxtst-dev \
  libatk-bridge2.0-dev \
  libdrm-dev \
  libgbm-dev \
  wget \
  unzip \
  x11-utils \
  x11-xserver-utils \
  xdg-utils \
  libgl1 \
  && apt-get clean

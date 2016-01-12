FROM videosegment:dev

# Install core deps
RUN apt-get install -y \
	cmake \
	cmake-curses-gui

RUN apt-get install -y \
  build-essential	\
  cmake	\
  git-core \
  libavcodec-dev \
  libavformat-dev \
	libboost-all-dev \
  libgflags-dev \
  libgoogle-glog-dev \
  libgtk2.0-dev \
  libjsoncpp-dev \
  libprotobuf-dev \
  libprotoc-dev \
  libswscale-dev \
  protobuf-compiler \
  yasm

RUN add-apt-repository ppa:mc3man/trusty-media
RUN apt-get update && apt-get install -y \
  ffmpeg \
  libeigen3-dev \
  libopencv-dev

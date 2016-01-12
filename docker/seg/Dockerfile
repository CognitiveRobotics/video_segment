FROM videosegment:dep

WORKDIR /opt

# Clone the Caffe repo
RUN git clone https://github.com/CognitiveRobotics/video_segment.git

RUN cd video_segment && \
  mkdir build && \
	cd build && \
	cmake ../seg_tree_sample && \
	make

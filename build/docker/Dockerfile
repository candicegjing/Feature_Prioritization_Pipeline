FROM knowengdev/base_image:09_19_2017

ENV SRC_LOC /home

# Install the latest knpackage
RUN pip3 install -I knpackage redis

# Clone from github
RUN git clone https://github.com/KnowEnG/Feature_Prioritization_Pipeline.git ${SRC_LOC} 

# Set up working directory
WORKDIR ${SRC_LOC}

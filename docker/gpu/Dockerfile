FROM nvidia/cuda:9.0-cudnn7-runtime

RUN apt update && apt install -y python3-pip && \
    apt install -y wget vim git
RUN pip3 install tensorflow-gpu keras
RUN pip3 install --quiet tensorflow-hub
RUN pip3 install seaborn
RUN apt install -y python3-tk

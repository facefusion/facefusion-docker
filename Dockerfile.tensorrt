FROM nvidia/cuda:12.8.1-cudnn-runtime-ubuntu24.04

ARG FACEFUSION_VERSION=3.1.2
ENV GRADIO_SERVER_NAME=0.0.0.0
ENV PIP_BREAK_SYSTEM_PACKAGES=1
ENV LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/lib/python3.12/dist-packages/tensorrt_libs

WORKDIR /facefusion

RUN apt-get update
RUN apt-get install python3.12 -y
RUN apt-get install python-is-python3 -y
RUN apt-get install pip -y
RUN apt-get install git -y
RUN apt-get install curl -y
RUN apt-get install ffmpeg -y
RUN pip install tensorrt==10.8.0.43 --extra-index-url https://pypi.nvidia.com

RUN git clone https://github.com/facefusion/facefusion.git --branch ${FACEFUSION_VERSION} --single-branch .
RUN python install.py --onnxruntime cuda --skip-conda

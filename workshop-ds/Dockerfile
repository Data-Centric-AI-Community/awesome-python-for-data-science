FROM continuumio/miniconda3:22.11.1-alpine

WORKDIR /workshop-odsc

COPY environment.yaml environment.yaml
RUN conda env create -f environment.yaml

RUN echo "conda activate workshop-odsc" >> ~/.bashrc

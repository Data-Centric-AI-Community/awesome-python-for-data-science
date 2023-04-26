FROM continuumio/miniconda3:22.11.1-alpine

WORKDIR /workshop-odsc

COPY environment.yaml environment.yaml
RUN conda env create -f environment.yaml
RUN conda clean -afy && \
    find /opt/conda/ -follow -type f -name '*.a' -delete && \
    find /opt/conda/ -follow -type f -name '*.js.map' -delete

RUN echo "conda activate workshop-odsc" >> ~/.bashrc

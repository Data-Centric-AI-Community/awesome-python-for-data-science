FROM centos:7

WORKDIR /workshop-odsc

RUN curl -O https://repo.anaconda.com/miniconda/Miniconda3-py310_23.1.0-1-Linux-x86_64.sh
RUN chmod +x ./Miniconda3-py310_23.1.0-1-Linux-x86_64.sh
RUN ./Miniconda3-py310_23.1.0-1-Linux-x86_64.sh -b -p /opt/conda
RUN rm Miniconda3-py310_23.1.0-1-Linux-x86_64.sh

ENV PATH /opt/conda/bin:$PATH

COPY environment.yaml environment.yaml
RUN conda env create -f environment.yaml

RUN conda init bash 
RUN echo "conda activate workshop-odsc" >> ~/.bashrc

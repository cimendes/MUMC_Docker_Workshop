# Dockerfile reference documentation
# https://docs.docker.com/engine/reference/builder/

# Base image - Alternatives: Conda, Python...
FROM continuumio/miniconda3

# Metadata - optional
LABEL base.image="miniconda3"
LABEL version="0.1"
LABEL software="canu"
LABEL software.version="2.1"
LABEL description="First example - Docker workshop Canu Assembler"
LABEL website="https://github.com/marbl/canu"
LABEL documentation=""
LABEL license=""
LABEL tags=""

# Maintainer
MAINTAINER Inês Mendes <cimendes@medicina.ulisboa.pt>

# System essentials
RUN conda install -c conda-forge -c bioconda -c defaults canu

# Set up workdir for installation 
WORKDIR /data

# Dependencies

# Instalation

# Set up Path
#ENV PATH="/NGStools:$PATH"

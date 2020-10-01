# Dockerfile reference documentation
# https://docs.docker.com/engine/reference/builder/

# Base image - Alternatives: Conda, Python...
FROM ubuntu:16.04

# Metadata
LABEL base.image="ubuntu"
LABEL version="0.1"
LABEL software=""
LABEL software.version=""
LABEL description="First example - Docker workshop"
LABEL website=""
LABEL documentation=""
LABEL license=""
LABEL tags=""

# Maintainer
MAINTAINER Inês Mendes <cimendes@medicina.ulisboa.pt>

# System essentials
RUN apt-get update && apt-get -y install build-essential \
                                 git 

# Set up workdir for installation 
WORKDIR /NGStools

# Dependencies

# Instalation

# Set up Path
ENV PATH="/NGStools:$PATH"

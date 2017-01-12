FROM jupyter/datascience-notebook

MAINTAINER Hélain Schoonjans <helain.schoonjans@outlook.com>

RUN pip install sexmachine

# install python packages
RUN conda install --quiet --yes \
    'networkx=1.11*' \
    'nltk=3.2*' && \
    conda clean -tipsy


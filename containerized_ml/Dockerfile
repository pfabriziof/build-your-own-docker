# This could be called Containerfile, but Dockerfile is for compatibility purposes
FROM docker.io/jupyter/tensorflow-notebook

USER root

RUN pip install --upgrade pip && \
    pip install transformers pysrt

USER ${NB_UID}

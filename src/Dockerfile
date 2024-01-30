FROM jupyter/tensorflow-notebook

USER $NB_UID

RUN pip install --upgrade pip && \
    pip install tensorflow-hub && \
    pip install opencv-python && \
    fix-permissions "/home/${NB_USER}"
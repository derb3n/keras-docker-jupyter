FROM jupyter/scipy-notebook

RUN python --version
#RUN conda install keras
# RUN conda install -c conda-forge preprocess 
# RUN pip install BeautifulSoup4
RUN pip install --upgrade pip
RUN pip install --upgrade keras
RUN pip install --upgrade tensorflow
RUN pip install --upgrade opencv-contrib-python
# THEMES: https://github.com/dunovank/jupyter-themes
RUN pip install jupyterthemes
RUN pip install --upgrade jupyterthemes
RUN jt -t monokai -T -N -nfs 11 -fs 9

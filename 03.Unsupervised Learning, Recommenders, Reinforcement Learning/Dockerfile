FROM tensorflow/tensorflow:2.16.1-gpu-jupyter
MAINTAINER Amuro
RUN echo 'Build reinforcement Learning Class image' && pip install gymnasium imageio imageio[ffmpeg] pandas pyvirtualdisplay swig bokeh plotly tf_keras && apt install -y --force-yes --no-install-recommends xvfb && pip install -U scikit-learn gymnasium[box2d]

FROM continuumio/anaconda3
RUN conda install BeautifulSoup4
RUN conda install -c conda-forge cufflinks-py -y
RUN conda install jupyter -y --quiet
RUN conda install tensorflow -y
RUN conda install tensorboard -y
#RUN conda activate tf-gpu
#SHELL ["conda", "run", "-n", "tf-gpu", "/bin/bash", "-c"]
#RUN conda install jupyter -y --quiet
#RUN conda install ipykernel -y
#RUN conda install pandas -y
#RUN python -m ipykernel install --user --name python-tf-gpu --display-name "Python (tf-gpu)"
#RUN conda install seaborn -y
#RUN conda install scikit-learn -y
#RUN conda install tensorboard

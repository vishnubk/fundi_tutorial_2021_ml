# fundi_tutorial_2021_ml
Hands-On Machine Learning Tutorial for Pulsar Candidate Classification

General Download Instructions.

1. Clone this repo. (git clone https://github.com/vishnubk/fundi_tutorial_2021_ml.git)
2. Download the Data from MPIfR FTP Server and untar it. (wget ftp.mpifr-bonn.mpg.de:outgoing/vishnu/fundi_tutorial_data.tar.gz)
3. Ensure the three directories input_data, test_data and training_data are in the same directory as this repo.
4. docker run -it -p 8888:8888 -v ~/fundi_tutorial_2021_ml:/opt/fundi_tutorial_2021_ml/ vishnubk/fundi_tutorial_2021_ml /bin/bash -c "jupyter notebook --notebook-dir=/opt/fundi_tutorial_2021_ml/ --ip='*' --port=8888 --no-browser --allow-root"

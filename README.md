# fundi_tutorial_2021_ml
Hands-On Machine Learning Tutorial for Pulsar Candidate Classification

General Download Instructions.

1. Clone this repo. (git clone https://github.com/vishnubk/fundi_tutorial_2021_ml.git)
2. Download the Data from MPIfR FTP Server. (wget -r ftp.mpifr-bonn.mpg.de:outgoing/vishnu/fundi_tutorial/*)
3. If step 2 is taking too long, then download it from GDrive (https://drive.google.com/drive/folders/10E3zmx87HKI7DwH2FD5hYxmEUIYx_foZ?usp=sharing). 
4. Ensure the three directories input_data, test_data and training_data are in the same directory as this repo.
5. docker run -it -p 8888:8888 -v your_host_path/fundi_tutorial_2021_ml:/opt/fundi_tutorial_2021_ml/ fundi_ml_tutorial_2021 /bin/bash -c "jupyter notebook --notebook-dir=/opt/fundi_tutorial_2021_ml/ --ip='*' --port=8888 --no-browser --allow-root"

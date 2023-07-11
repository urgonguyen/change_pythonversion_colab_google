# change_pythonversion_colab_google
# first install python 3.6
!sudo apt-get update -y
!sudo apt-get install python3.6
# change alternatives
!sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 1
# select python version
!sudo update-alternatives --config python3
# check python version
!python --version
# install pip for new python 
!sudo apt-get install python3.6-distutils
!wget https://bootstrap.pypa.io/get-pip.py
!python get-pip.py
# upgrade pip
!sudo apt install python3-pip
!python -m pip install --upgrade pip

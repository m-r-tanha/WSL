# WSL
### access to Win via WSL
cd /mnt/c/Users/<windows.username>/Pictures

### Install Jupyter in WSL
sudo apt update && upgrade
sudo apt install python3 python3-pip ipython3
sudo apt install jupyter-core

#Check your version
python3 --version

#Upgrade pip
python3 -m pip install --upgrade pip
pip3 install jupyter

### Create a directory under root / and chown to your user:
  - sudo mkdir /project
  - sudo chown $USER:$USER /project

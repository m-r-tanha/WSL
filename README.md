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

### How to Copy Files from Windows 10 to Windows Sub-System for Linux and vice versa
- pwd
- mkdir test
- cd /mnt
- ls -l
- cd I (it is a partition in Windows)
- ls -l
- /mnt/i$ cd 'a folder name'
- cp * /home/m_r_tanha/test
- cd
- Or use WinSCP (https://linuxhint.com/copy-files-from-windows-ubuntu-wsl-same-host/)
### Error: -bash: ./configure: Permission denied
- chmod +x configure
- ls -l configure
### This command grants read, write, and execute permissions to everyone
-chmod -R 777 /path/to/folder

### run Jupyterin Ubunto
- jupyter lab

### create and active environment in Ubuntu
- python3 -m venv myenv
- source myenv/bin/activate
- python3 -m notebook

- deactivate

### Active and run Conda
- source ~/anaconda3/bin/activate
- 
### open explorer from Linux
- explorer.exe .
### edit a file in Ubuntu
- nano ~/.bashrc
- Make your changes in the file.
- To save the changes, press Ctrl + O, then press Enter.
- To exit Nano, press Ctrl + X.
### Unzip
unzip -q matlab_R2023b_glnxa64.zip -d matlab_for_UB

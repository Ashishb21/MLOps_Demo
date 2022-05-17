MLOPs Introduction 

create the conda env by using below commands 
```bash
conda create - n <envname> python=3.8 -y
conda activate <envname>
pip install -r requirements.txt
git init
dvc init
git add .
git commit -m "First commit "
git remote add origin <repo link.git>
git branch -M main
git push origin main
```
# MLOPS

# connect To Aws ec2 instance

ssh -i ~/path/to/mypemfile.pem ubuntu@ip

# Download Anaconda

wget [https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh](https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh)

# Install Anaconda

bash Anaconda3-2022.05-Linux-x86_64.sh

conda init yes
which python
It will anaconda python

# Install Docker

sudo apt install [docker.io](http://docker.io/)

# Update

sudo apt update

# Make a folder soft

mkdir soft

# Go into folder

cd soft

# Go to docker compose and find latest release of linux

wget [https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-linux-x86_64](https://github.com/docker/compose/releases/download/v2.5.0/docker-compose-linux-x86_64) -O docker-compose

# Make executable

chmod +x docker-compose

# Open bashrc file and set the path

vim .bashrc
export PATH="${HOME}/soft:${PATH}"
source .bashrc
which docker-compose

# Test and Check Docker

sudo docker run hello-world

# add user to group to avoid putting sudo everytime .

sudo groupadd docker
sudo usermod -aG docker $USER

# How to access remote from vscode

install extention - remote ssh
configure the .ssh/config file

# create folder notebbok

jupyter notebook

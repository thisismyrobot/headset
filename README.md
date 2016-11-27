# Headset


## Install (Raspi Zero)

```sh
sudo apt-get install git python-pip libffi-dev libssl-dev
git clone https://github.com/thisismyrobot/headset.git .
cd headset
pip install -r wssh/requirements_server.txt
```

## Start

```sh
cd wssh
bin/wsshd
```

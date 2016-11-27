# Headset

This codebase was created as a modification of
[wssh](https://github.com/aluzzardi/wssh) so uses its MIT licence.

## Install (Raspi Zero)

```sh
sudo apt-get install git python-pip libffi-dev libssl-dev
git clone --recursive https://github.com/thisismyrobot/headset.git
cd headset
pip install -r wssh/requirements_server.txt
```

## Start

```sh
cd wssh
bin/wsshd
```

# quick-install
Ubuntu set-up for CTF play

```
sudo apt install atom sublime-text vim gcc-multilib wireshark git python2.7 python-pip python-dev git libssl-dev libffi-dev build-essential
sudo dpkg-reconfigure wireshark-common
sudo snap install --classic code
git clone https://github.com/longld/peda.git ~/peda
echo "source ~/peda/peda.py" >> ~/.gdbinit
python -m pip install --upgrade pip
python -m pip install --pgrade pwntools
```

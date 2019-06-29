# usd-sandbox


# Diary


## 2019-06-29 - Friday


### Install Platform 
- Spent this evening installing CentOS 7 on a Virtual Machine
- Had issues with the resolution being stuck at 800x600
- For some reason the mouse died in the VM. Hence decided to switch to a Ubuntu VM instance
- CentOS 7 is a pain to setup compared to Ubuntu


### Build USD
Ubuntu

Needed to setup the following dependencies before I could build USD
```
python 2.7 (have been using python3 these days as my base py version, hence need to keep in mind about py2.7 for vfx)

sudo apt-get install qt4-qmake
sudo apt-get install libqt4-dev
python2 -m pip install PySide

python2 -m pip install PyOpenGL PyOpenGL_accelerate
sudo apt-get install libglew-dev libglfw3-dev libglfw3

```

# usd-sandbox


# Diary


## 2019-06-28 - Friday


### Install Platform 
- Spent this evening installing CentOS 7 on a Virtual Machine
- Had issues with the resolution being stuck at 800x600
- For some reason the mouse died in the VM. Hence decided to switch to a Ubuntu VM instance
- CentOS 7 is a pain to setup compared to Ubuntu


### Build USD
Ubuntu

Needed to setup the following dependencies before I could build USD
```
python 2.7 (have been using python3 these days as my base py version, 
hence need to keep in mind about py2.7 for vfx). 
Have been using Conda to activat a python 2.7 environ.

sudo apt-get install qt4-qmake
sudo apt-get install libqt4-dev
python2 -m pip install PySide

python2 -m pip install PyOpenGL PyOpenGL_accelerate
sudo apt-get install libglew-dev libglfw3-dev libglfw3

```

May look at creating a rez package to launch into a USD environ...

## 2019-06-29 - Saturday

Probably won't get much done today as I had Muai Thai this arvo and Have a bbq tonight.

Though, tomorrow I'll look at spinning up a fresh Ubuntu VM as the one I'm currently seems sluggish. 
Also, I'll probably look at reseting my host OS (kubuntu) as I think I've done too much customisation and have probably added too much bloat and tinkering to get kubuntu to work on my xps 15 laptop, 
Perhaps I should return to windows for my host OS 😞

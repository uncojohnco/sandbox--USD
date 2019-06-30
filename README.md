# usd-sandbox


# Diary

## 2019-06-28 - Thursday
Watched videos...
- [USD Building Asset Pipelines](https://www.youtube.com/watch?v=4W5D-IuRyaM)


## 2019-06-28 - Friday

### Install Platform 
- Spent this evening installing CentOS 7 on a Virtual Machine
- Had issues with the resolution being stuck at 800x600
- For some reason the mouse died in the VM. Hence decided to switch to a Ubuntu VM instance
- CentOS 7 is a pain to setup compared to Ubuntu 😞


### Build USD
Ubuntu

Needed to setup the following dependencies before I could build USD
```
git clone https://github.com/PixarAnimationStudios/USD.git

sudo apt install gcc
sudo apt install build-essential
sudo apt install cmake

sudo apt install qt4-qmake
sudo apt install libqt4-dev
audo apt install python-pip
python2 -m pip install PySide

python2 -m pip install PyOpenGL PyOpenGL_accelerate
sudo apt-get install libglew-dev libglfw3-dev libglfw3

```

May look at creating a rez package to launch into a USD environ...

## 2019-06-29 - Saturday

Probably won't get much done today as I had Muai Thai this arvo and Have a bbq tonight.

- Though, tomorrow I'll look at spinning up a fresh Ubuntu VM as the one I'm currently seems sluggish. 
- This is probably due to the various bloat I've added while doing prototype dev. In different domains i.e webdev, data analytics, machine learning, and musc personal projects. 🙃
- Also, I'll probably look at reseting my host OS (kubuntu) as I think I've done too much customisation and have probably added too much bloat and tinkering to get kubuntu to work on my xps 15 laptop, 
- Perhaps I should return to windows for my host OS 😞

## 2019-06-30 - Sunday

Morning...
- Woke up slightly dusty (had a few drinks at the BBQ last night...)
- Decided to wipe my laptop and installed kubuntu 19.04
- Setup a VM for USD with Ubuntu 18.04 LTS
- Next steps to setup USD on Ubuntu VM...

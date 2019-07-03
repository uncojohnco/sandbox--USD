# usd-sandbox

- https://github.com/PixarAnimationStudios/USD
- https://github.com/vfxpro99/usd-resources

## Projects
- [deployment](https://github.com/uncojohnco/usd-sandbox/projects/2)

## Diary

### 2019-06-28 - Thursday
Watched videos...
- [USD Building Asset Pipelines](https://www.youtube.com/watch?v=4W5D-IuRyaM)


### 2019-06-28 - Friday

#### Install Platform 
- Spent this evening installing CentOS 7 on a Virtual Machine
- Had issues with the resolution being stuck at 800x600
- For some reason the mouse died in the VM. Hence decided to switch to a Ubuntu VM instance
- CentOS 7 is a pain to setup compared to Ubuntu 😞


#### Build USD
Ubuntu 18.04 LTS

Needed to setup the following dependencies before I could build USD
```
git clone https://github.com/PixarAnimationStudios/USD.git

sudo apt install gcc
sudo apt install build-essential
sudo apt install cmake

# sudo apt install qt4-qmake
# sudo apt install libqt4-dev
# audo apt install python-pip
# python2 -m pip install PySide

sudo apt-get install pyside-tools

python2 -m pip install PyOpenGL # PyOpenGL_accelerate

sudo apt install zlib1g-dev
sudo apt install libglew-dev libglfw3-dev libglfw3
# sudo apt install libxcursor-dev
# sudo apt install libxinerama-dev
sudo apt install xorg-dev

sudo apt install libcanberra-gtk-module libcanberra-gtk3-module
```

May look at creating a rez package to launch into a USD environ...

### 2019-06-29 - Saturday

Probably won't get much done today as I had Muai Thai this arvo and Have a bbq tonight.

- Though, tomorrow I'll look at spinning up a fresh Ubuntu VM as the one I'm currently seems sluggish. 
- This is probably due to the various bloat I've added while doing prototype dev. In different domains i.e webdev, data analytics, machine learning, and musc personal projects. 🙃
- Also, I'll probably look at reseting my host OS (kubuntu) as I think I've done too much customisation and have probably added too much bloat and tinkering to get kubuntu to work on my xps 15 laptop, 
- Perhaps I should return to windows for my host OS 😞

### 2019-06-30 - Sunday

Morning...
- Woke up slightly dusty (had a few drinks at the BBQ last night...)
- Decided to wipe my laptop and installed kubuntu 19.04
- Setup a VM for USD with Ubuntu 18.04 LTS
- Next steps to setup USD on Ubuntu VM...

Afternoon...
- built USD
- When executing `usdview extras/usd/tutorials/convertingLayerFormats/Sphere.usda` the stageview is not rendering [stageview is blank/not rendering](https://github.com/uncojohnco/usd-sandbox/issues/13)
- May have to resort to installing USD on the host OS, though I'd rather not have to do this...
- TODO: Check out the pixar USD repo if anyone has posted similar issues...

### 2019-07-01 - Monday

 - Resolved [stageview is blank/not rendering](https://github.com/uncojohnco/usd-sandbox/issues/13)
 - Attempted to build Maya 2017 in ubuntu
  - followed the below gist, though Maya still keeps segfaulting on launch
  - https://gist.githubusercontent.com/nrtkbb/c6e8b71deb00ce19b9915714de87fc61/raw/f47d6a23dcd3625ba367f06f3aeeaee3ce92495c/maya2018install.sh
  
### 2019-07-01 - Tuesday

Evening
 - Was hopping to use an enviroment from work to ticker with USD. Unfortunatley this fell through as Maya kept crashing due to openGL issues when using the Teradici =\ 
 - Attempted to Install Maya 2017 again on my laptop with sucess this time around!
 - Now looking at building Maya_USD plugin...
 

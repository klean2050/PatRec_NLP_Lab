# Introduction to Python for Machine Learning
The repo includes the introductory classes in Python for Pattern Recognition, Speech and Language Processing, Neural Networks and other related courses in ECE NTUA. Material covers an introduction to Python, NumPy, matplotlib, Pandas, Tensorflow, Torch, scikit-learn etc. Some of the material is adapted from [this tutorial](http://cs231n.github.io/python-numpy-tutorial/) in cs231n course at Stanford.

### Virtual Machines
To ease the setup process we provide a virtual machine for each course with the required
software preinstalled. To run the virtual machine you need to download and install [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads). Then you need to open a terminal and run:
```
# For Pattern Recognition course
cd <path/to>/python-lab
cp Vagrantfile.patreco Vagrantfile
vagrant up
```
or
```
# For Speech and Language Processing course
cd <path/to>/python-lab
cp Vagrantfile.slp Vagrantfile
vagrant up
```
Setup will take a while, since it installs all dependencies. When the setup is finished, a jupyter notebook will start in the machine. Navigate to the URL printed. Changes to files will be saved automatically to your current working directory.

To access the console inside the VM use
```
vagrant ssh
```
To stop the VM use
```
vagrant halt
```

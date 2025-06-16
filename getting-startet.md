---
layout: default
title: Getting started
nav_order: 3
---

This site provides a short FAQ on how to get started with ColRev.

# How to install ColRev?
CoLRev is a Python package that can be installed with the following command: <br>
> pip install colrev

# Which Programms do I need?
In order to run ColRev on your System, you require the following 3 Programms, that are named below with their installation instructions.
1. Python: https://realpython.com/installing-python/
   
2. Git: https://github.com/git-guides/install-git
   
3. Docker: https://docs.docker.com/engine/install/


# How to get Docker working on your OS?
There may be some configuration needed to get Docker to work on your OS. If Docker doesn't have the required permissions on your maschine, try to run the following to give Docker the required permissions: <br>
> sudo gpasswd -a $USER docker <br>
> newgrp docker

# Notebooks
Welcome to the SciServer demo notebooks repository!

Here you will find sample Jupyter notebooks that you can load into your Compute containers. You can modify these demo notebooks as a starting point for your own notebooks. Note that you can only load the notebooks into one container at a time, although you can repeat the process to load them into other containers.

To load the notebooks into one of your containers, use the following steps:

1. Sign in to SciServer Compute (http://compute.sciserver.org) using your SciServer username and password.
2. Click on the name of the container into which you want to load the demo notebooks.
3. Once you are in the container, click on persistent to enter the container's persistent space. Any files you put in persistent will remain there across sessions.
4. Create a new folder inside the persistent space by clicking the "New" button, then selecting Folder.
5. Create a new notebook inside your new folder. Demo notebooks are available in Python or R.
6. In the first code box of your new notebook, type the following command exactly (with the initial exclamation point):

!git clone https://github.com/sciserver/Notebooks

7. After typing the command, immediately execute it by clicking the Play button. You can also use the keyboard shortcut to run (CTRL-enter on PC, CMD-enter on Mac).
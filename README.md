# Chameleon Bare Metal Artifact Environment

This notebook provisions a bare metal environment on Chameleon for examining a
selected software artifact. When the notebook is launched, a pre-selected Git
repository is passed as an argument and automatically cloned into your home
directory on the instance for you to explore and use.

To provision nodes, set up instances, and access the cloned repository in the
cloud, check out `Experiment.ipynb` in the file explorer in the left sidebar.

## Requirements

This environment requires a Chameleon account with an active project
allocation. If you are viewing this at `jupyter.chameleoncloud.org`, you
should be all set.

## Overview of Steps

1. __(Experiment.ipynb)__ Provision the environment:

    a. Obtain a reservation for a baremetal node

    b. Create an instance on that node

    c. Run setup to install needed programs and clone the selected repository
    into your home directory

2. __(Experiment.ipynb)__ Examine the artifact

    a. Explore the code and files in the cloned repository

    b. Run scripts or programs from the repository on the instance

## Disclaimer

While we have tried our best to keep our systems as robust as possible,
sometimes unexpected errors may arise. A fix for authorization errors may be
to relog (File > Log Out, then "Return to Jupyterhub"). Errors that may happen
while running specific cells are mentioned.

## Contact

Please contact help@chameleoncloud.org for general Chameleon support.

# Jupyter Notebook Quickstart

Jupyter Notebooks provide a way to share writing, code, and output together.
In this document, each cell may be one of these items. To reproduce this
environment setup and artifact examination, you should select each code block,
modify the contents if needed, and then run it. You can run a cell by clicking
it, then clicking the "play" button in the top bar, or by typing ctrl+enter.

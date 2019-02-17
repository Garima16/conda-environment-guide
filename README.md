# conda-environment-guide
frequently used commands for managing conda environment

## Creating new environment

To create a new environment with name 'opencvenv' with a specific version of Python:

`conda create -n opencvenv python=3.4`

## Installing Packages

To install a specific package such as 'opencv' into an existing environment:

`conda install -n opencvenv opencv`

To install the package in active environment:

`conda install scipy`

## Viewing list of installed packages

To list packages in active environment:

`conda list`

To list packages in a deactived environment:

`conda list -n opencvenv`



# conda-environment-guide
Commands guide for managing conda environment

## Installing Packages

To install a specific package such as 'opencv' into an existing environment "opencvenv":

`conda install --name opencvenv opencv`

To install the package in active environment

`conda install scipy`

## Viewing list of installed packages

To list packages in active environment:

`conda list`

To list packages in a deactived environment:

`conda list -n envname`

# ESW wrapper for HAPI
## wrapper for acq400_hapi creates installable package for acq400 embedded system

## to update the acq400_hapi submodule : FIRST TIME
1. git submodule init
2. git submodule update

## subsequent times
1. cd acq400_hapi; git pull origin master

## build the package
./make.package

Package is included in PACKAGES.OPT for inclusion next release



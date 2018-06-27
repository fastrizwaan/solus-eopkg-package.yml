# solus-eopkg-package.yml
My Solus' package.yml files I use; required to build eopkg for Solus.

#build requirement
sudo eopkg it -c system.devel

# build the package
ypkg package.yml
ex. ypkg xcalib.yml

#install the built package
sudo eopkg it xcalib*.eopkg


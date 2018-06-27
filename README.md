# solus-eopkg-package.yml

My Solus' package.yml files I use; required to build eopkg for Solus.

1. build requirement

> sudo eopkg it -c system.devel

1. build the package

>ypkg package.yml
>ex. ypkg xcalib.yml

1. install the built package

>sudo eopkg it xcalib*.eopkg


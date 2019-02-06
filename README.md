hdf5-env
======
Configuration Environment for HDF5


## Requirements
* autotools

[comment]: # * cmake (for v7.0)
[comment]: #* autotools (up to v6.4)

## Rules

One can install lmfit with the following orders:

```
hdf5-env$ make init
hdf5-env$ make build
hdf5-env$ make install
```


For CentOS, one should run the following also

```
hdf5-env$ make setup
```

All files are installed in /usr/local/{lib,include,man}



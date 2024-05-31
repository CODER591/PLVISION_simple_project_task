# SIMPLE PROJECT.


To setup the project use the `setup_project_build.sh` script located at folder.

## Building Project:

### Building the project from scratch
``` bash
$ ./setup_project_build.sh
$ make all
```

### Building installing the project from scratch
``` bash
$ ./setup_project_build.sh
$ make all
$ make install
```

### Building installing the project from scratch
``` bash
$ ./setup_project_build.sh
$ make all
$ make install
```

### How to uninstall:
``` bash
$ make uninstall
```

### How to cleanup every file except the source:
It will:
- clean all build files
- clean all automake generated ones
- uninstall the app from /usr/local/bin.
``` bash
$ make clean-all
```



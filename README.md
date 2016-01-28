This package is merely a copy of the OpenSceneGraph DAE plugin.
It can be used to compile only the DAE plugin and link it to the 
OpenSceneGraph version on the repository.

This package is requires OpenSceneGraph 3.2.0 and is probably only for UNIX
systems.

Please refers to the OpenSceneGraph project for more information.

# Compiling
You must specify the CMake variables COLLADA_DYNAMIC_LIBRARY and
COLLADA_INCLUDE_DIR. You can use something like:

```
cmake  -DCOLLADA_DYNAMIC_LIBRARY=${INSTALL_DIR}/lib/libcollada14dom.so -DCOLLADA_INCLUDE_DIR=${INSTALL_DIR}/install/include/collada-dom ..
```

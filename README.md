# get_mesh_py_API
using pybind11 to create get_mesh python API

# How to use
```
mkdir build
cd build
cmake ..
make -j4
```
You will get a .so file.

# Note
Remember change include path in CMakeLists.txt. This code reply on Eigen and OpenMesh.

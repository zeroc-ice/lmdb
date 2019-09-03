# LMDB-TOOLS

This package contains the lmdb tools for lmdb 0.9.24, it was build with MSYS2 MinGW64 G++ 6.3.0.

## Source

The source code used to build this package is available at https://github.com/zeroc-ice/lmdb/tree/msvc.

## Build Instructions
```
git clone git@github.com:zeroc-ice/lmdb.git -b msvc
```

Open MSYS2 command promp
```
cd lmdb/libraries/liblmdb
make
```

Open Visual Studio Command Promp
```
cd lmdb
MSBuild libraries\liblmdb\msbuild\lmdb.proj /t:ToolsNugetPack
```

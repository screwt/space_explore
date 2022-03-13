# SpaceExplore

A space exploratory game using Ogre3D v2.3.
Solar systemes and objects are proceduraly generated: https://www.youtube.com/watch?v=ZZY9YE7rZJw&t=395s

## Build

Prérequiste, ofre3D 2-3 installed from the script "Quick Start scripts for Ogre 2.3" see page: https://www.ogre3d.org/download/sdk/sdk-ogre-next


```
mkdir build
cd build
cmake .. -DCMAKE_BUILD_TYPE=Debug -DOGRE_BINARIES=./Dependencies/Ogre/build/Debug -DOGRE_SOURCE=./Dependencies/Ogre
```

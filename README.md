fork from https://github.com/RainerKuemmerle/g2o

for ios build

my command list

1. vim CMakeLists.txt

  - OPTION (BUILD_SHARED_LIBS "Build Shared Libraries (preferred and required for the g2o plugin system)" ON)

  + OPTION (BUILD_SHARED_LIBS "Build Shared Libraries (preferred and required for the g2o plugin system)" OFF)

2. mkdir build-static
3. cd build-static
4. cmake -GXcode ..
5. open with xcode
5. some xcode modify config

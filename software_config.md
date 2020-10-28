## 1. cmake

### 1.1 via command-line

```
sudo apt-get install cmake

Version 3.5.1 for ubuntu16.04
```


### 1.2 via source code

```
- ./bootstrap
- make
- sudo make install
```

## 2. boost

### 2.1 check boost version

- dpkg -s libboost-dev | grep Version
- pkg-config --modversion boost
- cat /usr/include/boost/version.hpp | grep "BOOST_LIB_VERSION"

### 2.2 via command-line

```
sudo apt-get install libboost-all-dev

Version 1.58.0 for ubuntu16.04
```

### 2.3 via source code

## 3. eigen

### 3.1 check eigen version

### 3.2 via command-line

```
sudo apt-get install libeigen3-dev

Version 3.2.92 for ubuntu16.04
```

### 3.3 via source code


6. install gtest (Version 1.8.1)

```
source file: googletest-release-1.8.1.zip

- mkdir build && cd build
- cmake ..
- make
- sudo cp googlemock/gtest/libgtest.a googlemock/gtest/libgtest_main.a /usr/local/lib
- sudo cp -a ../googletest/include/gtest/ /usr/local/include/gtest
```
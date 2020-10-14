






6. install gtest (Version 1.8.1)

```
source file: googletest-release-1.8.1.zip

- mkdir build && cd build
- cmake ..
- make
- sudo cp googlemock/gtest/libgtest.a googlemock/gtest/libgtest_main.a /usr/local/lib
- sudo cp -a ../googletest/include/gtest/ /usr/local/include/gtest
```
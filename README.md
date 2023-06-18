# vcpkg-test-termux

```ignore
vcpkg install fmt
cmake . -Bbuild -DCMAKE_TOOLCHAIN_FILE=$VCPKG_ROOT/scripts/buildsystems/vcpkg.cmake
cmake --build build
./build/main
```

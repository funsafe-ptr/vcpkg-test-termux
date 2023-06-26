# vcpkg-test-termux

```ignore
vcpkg install fmt:arm64-android
cmake . -Bbuild -DCMAKE_TOOLCHAIN_FILE=$VCPKG_ROOT/scripts/buildsystems/vcpkg.cmake
cmake --build build
./build/main
```

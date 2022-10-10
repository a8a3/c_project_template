## meson-based C project template ##

### features: ###
- gtest
- clang-format
- clang-tidy

### how to build: ###
1. meson setup build
2. cd build
3. meson compile
4. ninja -C . clang-format
5. ninja -C . clang-tidy
## CMake
```shell
cd sample
cmake -S . -B build
cmake --build build
build/main
```

```shell
rm -rf build
```

## Bazel
```shell
cd sample
bazel build :all
bazel run :all
```

```shell
rm -rf bazel-*
```

## Script

```shell
chmod +x  ./scripts/run.sh
./scripts/run.sh
```
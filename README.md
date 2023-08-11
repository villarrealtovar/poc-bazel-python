# install bazelisk

On Mac:
```command
# brew install bazelisk
```

# Initial Setup
Define two files: `.bazelversion` and `WORKSPACE.bazel`

## .bazelversion
Bazel version to use, e.g. `4.2.4`

## WORKSPACE.bazel
Empty file

# Useful commands

```command
# bazel --version
```

```
# bazel build //...

# bazel build //projects/projectA/... 
```
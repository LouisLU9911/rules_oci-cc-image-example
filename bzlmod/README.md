# bzlmod

## Prerequisites

* `bazel>=6.2.0`

## Build

You need to add `--enable_bzlmod` for you `bazel build`.

```bash
$ bazel build --enable_bzlmod :image
```

Or you could simple add it to your `.bazelrc`.

```bash
$ cat .bazelrc
build --enable_bzlmod

# build
$ bazel build :image
```

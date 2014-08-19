The repository contains all Planitar docker images. This is a central place to
build, push and update the images.

# Get the images

```shell
git clone https://github.com/PlanitarInc/docker-images
cd docker-images
git submodule init
git submodule update
```

# Rebuild the images

```shell
./gen-dep.py > Makefile && make
```

# Push new images

```shell
./gen-dep.py > Makefile && make push
```

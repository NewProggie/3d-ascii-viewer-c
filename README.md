# 3d-ascii-viewer-c

Viewer of 3D models in ASCII, written in C.

![Example usage capture.](capture.gif)

**Note**: Currently, the program only supports [Wavefront .obj](https://en.wikipedia.org/wiki/Wavefront_.obj_file) files.

## Compile an run the program

You need developer's libraries for ncurses (the `libncurses-dev` package on Debian).

Compile the program using the `make` command:

```
$ make
```

You can try it passing any of the models in the `models` folder as an argument:

```
$ ./3d-ascii-viewer models/fox.obj
```

For additional options pass the `--help` option.

```
$ ./3d-ascii-viewer --help
```

## Models

* [Fox and ShibaInu models](https://opengameart.org/content/fox-and-shiba) made by PixelMannen for the Public Domain (CC0).
* [Tree models](https://opengameart.org/content/fox-trees-pack) made by Lokesh Mehra (mehrasaur) for the Public Domain (CC0).

ASCII luminescence idea by: [a1k0n.net](https://www.a1k0n.net/2011/07/20/donut-math.html)

## Older version

There is also an [older version](https://github.com/autopawn/3d-ascii-viewer-haskell), written in Haskell.

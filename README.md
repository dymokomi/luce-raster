# luce-raster

The pixel model shared by Luce's image codecs: Raster, chunks, sample types, a byte reader and buffer, and the codec error codes.

Split out of luce-image on 2026-09-22 so every file format is its own package, like luce-svg and luce-psd. luce-image depends on it for `Image.open`/`save`.

```
./test.sh    # the module's test blocks in native and C modes
```

Automated builds of `Graphviz` (x86, x64 and ARM64) using vcpkg.

Compiled using the Static C Runtime (`/MT`) with Control Flow Guard (CFG) enabled.

Includes pre-generated `config8` mapping layouts and formatted in a `$arch\` directory structure.

To obtain the latest release in a build environment:

```
cd path\to\Graphviz
del graphviz.zip
curl -LJO https://github.com/MediaArea/Graphviz-Windows/releases/latest/download/graphviz.zip
tar -xf graphviz.zip
```

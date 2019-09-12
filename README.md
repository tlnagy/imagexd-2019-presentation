# imagexd-2019-presentation

## Usage

Please install [Julia](https://julialang.org/downloads/) and `IJulia` to
use with `jupyter` notebook.

## Build instructions

The presentation is built from the jupyter notebook using the following
`nbconvert` command:

```
jupyter nbconvert multidimensional_images_in_julia.ipynb --to slides --post serve --SlidesExporter.reveal_theme=serif --SlidesExporter.reveal_transition=none
```

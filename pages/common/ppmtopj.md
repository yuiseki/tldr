# ppmtopj

> Convert a PPM file to an HP PaintJet file.
> More information: <https://netpbm.sourceforge.net/doc/ppmtopj.html>.

- Convert a PPM file to an HP PaintJet file:

`ppmtopj {{path/to/input.ppm}} > {{path/to/output.pj}}`

- Move the image in the x and y direction:

`ppmtopj {{[-x|-xpos]}} {{dx}} {{[-y|-ypos]}} {{dy}} {{path/to/input.ppm}} > {{path/to/output.pj}}`

- Explicitly specify a gamma value:

`ppmtopj {{[-g|-gamma]}} {{gamma}} {{path/to/input.ppm}} > {{path/to/output.pj}}`

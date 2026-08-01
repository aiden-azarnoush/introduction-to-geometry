# Introduction to Geometry

Beamer lecture slides for an introductory geometry course, originally taught at St. Petersburg College (Fall 2021). The deck runs about 109 slides across four parts, with figures drawn in TikZ and worked examples throughout. **[View the compiled slides (PDF)](introduction_to_geometry_Aiden_Azarnoush.pdf)** — no LaTeX required.

## Contents

**Part 1 - Points, Lines, and Angles**
History of geometry, Euclidean vs non-Euclidean geometry, points, lines, rays, and planes, measuring angles (degrees and radians), complementary, supplementary, vertical, and adjacent angles, parallel lines cut by a transversal.

**Part 2 - Polygons and Triangles**
Polygons and regular polygons, interior and exterior angle sums, types of triangles, quadrilaterals (parallelogram, rectangle, rhombus, square, trapezoid).

**Part 3 - Perimeter, Area, and Circles**
Perimeter and area definitions, area formulas for rectangles, triangles, parallelograms, and trapezoids, circles, pi, circumference, and the area of a circle via Archimedes' argument.

**Part 4 - Solid Geometry**
Polyhedra, prisms, and pyramids, Euler's formula, Platonic solids, volume and surface area of boxes, prisms, pyramids, cylinders, cones, and spheres.

## Project structure

```
main.tex          # Entry point; inputs preamble, title, and slide parts
preamble.tex      # Packages, theme, and custom commands
title.tex         # Title page information
slides/           # part_1.tex ... part_4.tex (the lecture content)
Tikz/             # TikZ source for the hand-drawn figures
pics/             # Images used in the slides
background/       # Slide background
```

## Building

Compile `main.tex` with pdfLaTeX. The easiest route is [Overleaf](https://www.overleaf.com): upload the project as a zip and hit compile. Locally, with a full TeX Live installation:

```
pdflatex main.tex
pdflatex main.tex
```

The deck uses the `fouriernc` font package (New Century Schoolbook text with Fourier math), included in full TeX Live distributions.

## License

Released under the [MIT License](LICENSE). Feel free to adapt these slides for your own courses; attribution is appreciated.

## Author

Aiden Azarnoush
[aiden-azarnoush.github.io](https://aiden-azarnoush.github.io)

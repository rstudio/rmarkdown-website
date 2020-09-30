R Markdown Definition:-

R Markdown provides an authoring framework for data science. You can use a single R Markdown file to both

save and execute code
generate high quality reports that can be shared with an audience

# R Markdown Website Example

This repository illustrates one way to create a simple website that includes multiple R Markdown documents. 

Features of the simple website include:

1. Multiple Rmd files are accessible from a global navigation bar (defined in `_navbar.html`)

2. The Rmd files share common output settings (including the directory where dependent libraries are written) defined in `_output.yaml`.

3. The site can be built using the included `Makefile`. An RStudio Project that binds building the Makefile to `Cmd+Shift+B` is also included.


---
title: Xpetra Doxygen
permalink: xpetra_doxygen.html
folder: mpi_x
show_sidebar: true
contact: Jonathan Hu (jhu@sandia.gov), Chris Siefert (csiefer@sandia.gov)
package: xpetra
doxygen: true
---

Development Doxygen for Xpetra is available [Here](http://trilinos.org/docs/dev/packages/xpetra/doc/html/index.html)  
Links to all available Trilinos release Doxygen collections for Xpetra are listed below.  
Trilinos Version:

{% for trilinos_version in site.trilinos_versions %}
[{{ trilinos_version }}]({{ "http://trilinos.org/docs/r" | append: trilinos_version | append: "/packages/" | append: page.package | append: "/doc/html/index.html" }}),{% endfor %}

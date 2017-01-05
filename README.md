GLEX is an OpenGL Extension Specification Parser which is used to turn OpenGL extension specification files into a set of compact C source files that can be easily included into existing projects to initialize only the desired extension or core API function pointers.

This is **version 2** of GLEX which parses the database `*.spec` / `*.tm` files while <a href="https://github.com/sschuberth/glex1">GLEX 1</a> parses the human-readable `*.txt` specification files. Both specification file types are linked from the <a href="http://www.opengl.org/registry/">OpenGL Registry</a>. As GLEX is written in PHP, it can be easily used from both the command line and via a web front-end.
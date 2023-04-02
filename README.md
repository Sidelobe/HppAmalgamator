```
╦ ╦┌─┐┌─┐  ╔═╗┌┬┐┌─┐┬  ┌─┐┌─┐┌┬┐┌─┐┌┬┐┌─┐┬─┐
╠═╣├─┘├─┘  ╠═╣│││├─┤│  │ ┬├─┤│││├─┤ │ │ │├┬┘
╩ ╩┴  ┴    ╩ ╩┴ ┴┴ ┴┴─┘└─┘┴ ┴┴ ┴┴ ┴ ┴ └─┘┴└─

```

### Combines C++ header files into a single, amalgamated header file.

![](https://img.shields.io/github/license/Sidelobe/Hyperbuffer)
![](https://img.shields.io/badge/Python-blue.svg?style=flat&logo=c%2B%2B)

[https://github.com/Sidelobe/HppAmalgamator](https://github.com/Sidelobe/HppAmalgamator)

This Python script merges all files in a C++ header-only library into a single header.

* It is designed to work in projects where one "top-level" header file is the main entry point / API
* Includes are recusively resolved and amalagamated in the correct order
* Include files are searched in the directory/subdirectories of the top-level header
* System includes (e.g. `#include <cmath>`) are only included once in the beginning




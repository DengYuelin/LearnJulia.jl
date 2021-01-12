# Package LearnJulia

| Status | Coverage |
| :----: | :----: |
| [![Build Status](https://travis-ci.org/tlienart/Ex.jl.svg?branch=master)](https://travis-ci.org/tlienart/Ex.jl) | [![codecov.io](http://codecov.io/github/tlienart/Ex.jl/coverage.svg?branch=master)](http://codecov.io/github/tlienart/Ex.jl?branch=master) |

## Environments
in pkg mode, `activate EnvironmentName`
## adding packages
in pkg mode \
to add packages, use `add PkgName`\
to add packages from github, `add https://github.com/JuliaLang/Example.jl`\
to check installed packages, use `status`\
to update packages, `update PkgName` or `up PkgName`\
to remove a package, `rm PkgName`



## create packages
Example of Julia package to go along with [these notes](https://tlienart.github.io/pub/julia/dev-pkg.html).

In pkg mode:\
to generate a package, `generate PkgName`, then `dev path\\to\\dir\\PkgName`\
to test a single package, in the package directory, `activate .`
and `activate` to exit current package\
And `test` to run all tests in `test\\runtests.jl`

### Modify web packages
`develop --local PackageName`
`free PackageName` To stop using local version.

## IJulia
To run julia in vscode using Jupyter Notebook, select julia.exe as the interpreter.

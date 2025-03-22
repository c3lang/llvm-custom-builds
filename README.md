This is a repo building LLVM, forked from https://github.com/wasmerio/llvm-custom-builds

This repository contains a small `build.sh` (or `build.ps1` for Windows 
PowerShell) script that builds LLVM. The version of LLVM is defined in the CI script.
The build is run by [Github
Actions](https://github.com/wasmerio/llvm-custom-builds/actions) on 4
platforms: Linux (Ubuntu, amd64 and aarch64), Darwin (macOS), and Windows (not used).
Builds are attached to [Github releases as
assets](https://github.com/wasmerio/llvm-custom-builds/releases).

# License

The entire project is under the MIT License. Please read [the `LICENSE` file][license].


[license]: https://github.com/c3lang/llvm-custom-builds/blob/master/LICENSE

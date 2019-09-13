# Conan LibreSSL

This repository contains the conan receipe that is used to build the LibreSSL packages at appcom.

For Infos about LibreSSL please visit [libressl.org](https://www.libressl.org/).

The library is licensed under the [ISC License](https://tldrlegal.com/license/-isc-license).

This repository is licensed under the [MIT License](LICENSE).

## macOS

To create a package for macOS you can run the conan command like this:

`conan create . libressl/2.7.4@appcom/stable -s os=Macos -s os.version=10.14 -s arch=x86_64 -s build_type=Release -o shared=False`

### Requirements

* [CMake](https://cmake.org/)
* [Conan](https://conan.io/)
* [Xcode](https://developer.apple.com/xcode/)

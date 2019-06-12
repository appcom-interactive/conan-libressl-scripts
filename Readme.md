# Conan LibreSSL

[![Build Status](https://travis-ci.com/Manromen/conan-libressl-scripts.svg?branch=master)](https://travis-ci.com/Manromen/conan-libressl-scripts)

This repository contains the conan receipe that is used to build the LibreSSL packages at [rgpaul bintray](https://bintray.com/manromen/rgpaul).

For Infos about LibreSSL please visit [libressl.org](https://www.libressl.org/).

The library is licensed under the [ISC License](https://tldrlegal.com/license/-isc-license).

This repository is licensed under the [MIT License](LICENSE).

## macOS

To create a package for macOS you can run the conan command like this:

`conan create . libressl/2.7.4@rgpaul/stable -s os=Macos -s os.version=10.14 -s arch=x86_64 -s build_type=Release -o shared=False`

### Requirements

* [CMake](https://cmake.org/)
* [Conan](https://conan.io/)
* [Xcode](https://developer.apple.com/xcode/)

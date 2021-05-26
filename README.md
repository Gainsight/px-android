[![N|Solid](https://app-dev.aptrinsic.com/home/gainsight-px-logo.svg)](https://app.aptrinsic.com)

## Android-SDK

![version](https://img.shields.io/badge/version-1.4.4-green.svg) ![version](https://img.shields.io/badge/version-1.4.5-green.svg)

## Installation
Android-SDK is available through Maven.

## Maven
Add the repository in build.gradle file (app level) and implement the dependency

```sh
repositories {
    ...
    maven {
        url "https://github.com/Gainsight/px-android/raw/main/"
    }
}

dependencies {
    ...
    implementation 'com.gainsight.px:mobile-sdk:1.4.5'
}
```

## Documentation

You can find usage documentation at https://support.gainsight.com/PX/Mobile/Mobile_Platforms.


## License

MIT License

Copyright (c) 2019 aptrinsic

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

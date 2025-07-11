[![N|Solid](https://app-dev.aptrinsic.com/home/gainsight-px-logo.svg)](https://app.aptrinsic.com)

## Android-SDK

![version](https://img.shields.io/badge/version-1.12.3-green.svg)

## Installation
Android-SDK is available through Maven.

1. Add the repository into build.gradle file
	* App level (root level repositories not buildscript)
		
		```sh
		repositories {
		    ...
		    maven {
		        url "https://github.com/Gainsight/px-android/raw/main/"
		    }
		}
		```
	* **Or** in project level (allprojects level repositories)

		```sh
		allprojects {
		    repositories {
		        ...
		        maven {
			        url "https://github.com/Gainsight/px-android/raw/main/"
			    }
		    }
		}
		```

2. Add the dependency to build.gradle file (App level)

	```sh
	dependencies {
	    ...
	    implementation 'com.gainsight.px:mobile-sdk:1.12.3'
	}
	```
	
## Documentation

You can find usage documentation [here](https://support.gainsight.com/PX/Mobile/Mobile_Platforms).

## Release Notes

Version 1.12.3

* Fixing Encryption/Decryption issues
* Aligning all User and Account fields with Web API

Version 1.12.2

* Fixing feature mapper crash

Version 1.12.1

* Add support for using Application Context

Version 1.12.0

* Stop collecting device and advertisment ids on android
* Fixing configuration issue with Hybrid SDK on android

Version 1.11.0

* Upgrading project Gradle and AGP versions
* Fixing bugs

Version 1.10.1

* If view has no id, but has string as tag - we'll use it as id
* Adding the exception thrown to ExceptionHandler values

Version 1.10.0

* Adding reset API call for recreating instance with new configuration
* Adding API to enable/disable engagements at runtime
* Fixing bugs

Version 1.9.0

* Adding support for Interval engagement scope

Version 1.8.0

* Adding support for Every time (Paywall) engagement scope

Version 1.7.5

* Fixing Reset functionality

Version 1.7.4

* Renaming Builder maxQueueSize
* Web JS Platforms initialization: supporting also maxQueueSize and host

Version 1.7.3

* Support tracking web view content (inside native app)
* Adding configuration for limiting persistent cache queue size
* Fixing bugs

Version 1.7.0

* Supporting Web JS platforms i.e: Ionic, Sencha, Cordova
* Filtering out non-SDK deep links
* Adding new datacenter

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

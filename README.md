#ofxOSXBoost for Boost 1.56.0  ![image](https://travis-ci.org/danoli3/ofxOSXBoost.svg?branch=master)

### Boost C++ Libraries 1.56.0 Pre-compiled for OSX
![image](https://github.com/danoli3/ofxOSXBoost/blob/master/ofxaddons_thumbnail.png)

- Addon with Boost 1.56.0 for OSX / Xcode 
- Precompiled library and Command to build yourself
- Master is currently a Fat Lib of All Standard Architectures
- Check Branches for others or to be specific 
- Designed for use as an open frameworks addon, however should definitely work for other OSX projects
- Built with clang++ and using libc++ and std=c++11
- License: See Boost License [LICENSE.MD](https://github.com/danoli3/ofxOSXBoost/blob/master/LICENSE.md)

============


### Where to checkout?

- For openframeworks: Checkout in the addons folder like so: addons/ofxOSXBoost
- For others: anywhere you please



============

### How To Link to an Xcode Project?

In Xcode Build Settings for your project:

- Add to Library Search Paths: ``` $(SRCROOT)/../../../addons/ofxOSXBoost/libs/boost/lib/osx ```
- Add to Header Search Paths:  ```$(SRCROOT)/../../../addons/ofxOSXBoost/libs/boost/include ```

If not openFrameworks just add the ``` libs/boost/include ``` to Header Search Paths and the  ``` libs/boost/lib/osx ``` to Library Search Paths



============

### Architectures in Pre-Build Library (Fat Lib)
See the other branches on this repository (All libc++ std=c11)

- x86_64 (64-bit intel)
- i386 (32-bit intel)

       



============

### How to Build?

1. You don't need to. This has the pre-compiled versions of BOOST for you to use
2. If you would prefer to build it yourself checkout the script included in the ``` scripts ``` directory.


=============

### How to use Build Script


- Download files (suggested you download the files to addons/ofxOSXBoost for openFrameworks)
- Double click and run scripts/build.command (this will download the 1.56.0 version of boost and begin compiling the library).
- Once completed in the terminal continue with the next steps.
- Add the ofxOSXBoost to your project (src and libs for your chosen architecture)



============

#### Documentation on Boost 1.56.0


See: http://www.boost.org/users/history/version_1_56_0.html


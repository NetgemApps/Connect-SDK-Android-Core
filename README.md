# Connect SDK Core (Android)
The Connect SDK Core contains all of the core classes required for basic operation of Connect SDK. The core also includes support for some select protocols which do not have any heavy and/or external dependencies. These protocols include:
- Apple TV
- DIAL
- DLNA
- LG Netcast
- LG webOS
- LG Cast
- Roku

## General Information
For more information about Connect SDK, visit the [main repository](https://github.com/ConnectSDK/Connect-SDK-Android).

## Setup
Unless you are doing very specialized work to extend the SDK, you should not need to make direct use of this repository. Instead, clone the [main repository](https://github.com/ConnectSDK/Connect-SDK-Android), which includes this repository as a submodule.

## External libraries
libgstreamer_android.so is shared object library and links dynamically GStreamer open-source multimedia framework that is licensed under Lesser General Public License.
You can download and rebuild libgstreamer_android.so at [libgstreamer_android.tar](https://github.com/ConnectSDK/Connect-SDK-Android-Core/blob/master/jniLibs/libgstreamer_android.tar)
To build a new version of libgstreamer, follow instructions on [GStreamer Android](https://gstreamer.freedesktop.org/documentation/installing/for-android-development.html?gi-language=c).

## License
Copyright (c) 2013-2015 LG Electronics.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

> http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


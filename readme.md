Light Host
---

A simple VST/AU host for OS X, Windows, and Linux that sits in the menu/task bar.

### Features

See [#1](https://github.com/rolandoislas/LightHost/issues/1)

### Screenshot

![Light Host 1.2](http://i.imgur.com/UF9SWfC.jpg)

### Building

You need CMake and MSBuild. (CMake list could definitely be improved though from [this commit in another fork](https://github.com/koteq/LightHost/commit/edd7c2f209cdaf69e10c16e674f853845bcb4caa))

The [VST2.4](https://archive.org/download/VST2SDK) and [ASIO](https://www.steinberg.net/developers/asiosdk-open/) SDKs are required, and must be at the following paths:
 - VST 2.4: `C:\SDKs\vstsdk2.4`
 - ASIO: `C:\SDKs\asiosdk`

Run `cmake -Bbuild build` then `cmake --build build`
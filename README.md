## SoulverCore Multiplatform

This repository contains releases of [SoulverCore](https://github.com/soulverteam/SoulverCore) built for non-Apple platforms.

### Supported Platforms

| Platform | Architectures | Format |
|---|---|---|
| **Linux** | x86_64, ARM64 | `.so` (shared library) |
| **Android** | aarch64, x86_64 | `.so` (shared library) |
| **Windows** | x86, ARM | `.dll` + `.lib` |

### Downloads

See the [Releases](https://github.com/soulverteam/SoulverCore-Multiplatform/releases) page for the latest builds.

Each release zip contains:
- The SoulverCore dynamic library (`.so` or `.dll`)
- The `SoulverCore_SoulverCore.resources` bundle (required at runtime)
- Windows builds also include a `.lib` import library, `.swiftinterface`, and Swift runtime dependencies

### Usage

More details about SoulverCore, including how to use the API and license information, can be found in the main [SoulverCore repository](https://github.com/soulverteam/SoulverCore).

### Build Details

Android builds use the official [Swift SDK for Android](https://www.swift.org/documentation/articles/swift-sdk-for-android-getting-started.html) (Swift 6.3+).

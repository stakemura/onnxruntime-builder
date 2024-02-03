# onnxruntime-builder

Build [**minimal** ONNX Runtime](https://onnxruntime.ai/docs/build/custom.html#minimal-build) with GitHub Actions.

This repository is derived from [VOICEVOX/onnxruntime-builder](https://github.com/VOICEVOX/onnxruntime-builder).

## Supported Platforms

You can download the archived files of the runtime binaries from [Releases](https://github.com/stakemura/onnxruntime-builder/releases).

| Platform | Type   | ABI         |  Archived file         |
|----------|--------|-------------|---------------------------------------|
| Android  | .so    | armeabi-v7a | `onnxruntime-runtime-android-arm-*.tgz` |
| Android  | .so    | arm64-v8a   | `onnxruntime-runtime-android-arm64-*.tgz` |
| Android  | .so    | x86_64      | `onnxruntime-runtime-android-x86_64-*.tgz` |
| Android  | .aar   | armeabi-v7, aarm64-v8a, x86_64 | `onnxruntime-runtime-android-aar-*.tgz` |
| iOS      | .xcframework | arm64, x86_64 | `onnxruntime-runtime-ios-xcframework-*.zip`|
| Linux    | .so    | armv7l      | `onnxruntime-runtime-linux-armhf-*.tgz` |
| Linux    | .so    | aarch64     | `onnxruntime-runtime-linux-arm64-*.tgz` |
| Linux    | .so    | x64         | `onnxruntime-runtime-linux-x64-*.tgz` |
| macOS    | .dylib | universal (arm64, x86_64) | `onnxruntime-runtime-osx-universal2-*.tgz` |
| macOS    | .dylib | arm64       | `onnxruntime-runtime-osx-arm64-*.tgz` |
| macOS    | .dylib | x86_64      | `onnxruntime-runtime-osx-x86_64-*.tgz` |
| Windows  | .dll   | x64         | `onnxruntime-runtime-win-x64-*.tgz` |

## License

MIT License

## How to contribute

Open an issue or create a pull request.

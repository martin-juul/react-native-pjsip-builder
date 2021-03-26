# react-native-pjsip-builder
Easily build PJSIP with: OpenSSL, OpenH264, Opus and G.729 for Android and iOS, by using Docker and xcode.

## Versions
| Library              | Version |
|----------------------|---------|
| Android API          | 26      |
| Android NDK          | r21d    |
| PJSIP                | 2.10    |
| OPENSSL              | 1.1.1k  |
| OPENH264             | 2.1.1   | 
| OPUS                 | 1.3.1   |

## Build for Android

```bash
git clone https://github.com/martin-juul/react-native-pjsip-builder.git
cd react-native-pjsip-builder; ./build_android
```

Before starting the build, you will need to copy you Android SDK licenses file from your local SDK installation to `./android/android-sdk-licenses`. See [this page](https://developer.android.com/studio/intro/update.html#download-with-gradle) for more info.

Once you've got that file in place, run `./build_android` to start the process.

## Build for iOS

The iOS build is provided by https://github.com/VoIPGRID/Vialer-pjsip-iOS

```bash
./build_ios.sh
```

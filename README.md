# NativeBlobDetector
[![Build Status](https://travis-ci.com/serivesmejia/NativeBlobDetector.svg?branch=master)](https://travis-ci.com/serivesmejia/NativeBlobDetector)
[![](https://jitpack.io/v/serivesmejia/NativeBlobDetector.svg)](https://jitpack.io/#serivesmejia/NativeBlobDetector)

# 🤷‍️ What is this?

This library includes Java bindings for the SimpleBlobDetector to EasyOpenCV, since for some reason it lacks of this feature. It also provides a better way of instantating it by using a Parameters class, which is missing in the original OpenCV bindings.

## 📦 Installation (Credit to DogeCV)

### Gradle

#### This library requires [EasyOpenCV](https://github.com/OpenFTC/EasyOpenCV) already preinstalled
1. Pull up Android Studio, with the FTC application SDK open
2. Go to the root `build.gradle`
3. To the repositories section, add the lines 
```groovy
allprojects {
  repositories {
    maven { url 'https://jitpack.io' } // this line!
  }
}
```
3. Add the line `implementation 'com.github.serivesmejia:NativeBlobDetector:1.0.0'` to TeamCode's `build.release.gradle`, inside the dependencies block
7. Press the `Sync Now` button that will appear in the top right

### Native Library on the phone

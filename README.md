# frameworks-support

This repo is a mirror of https://android.googlesource.com/platform/frameworks/support.

## Purpose

If you want to read the source code of Android Support Library,
you have to checkout the source code from https://android.googlesource.com/platform/frameworks/support.
Though the official source code supports Gradle,
you have to do some modifications before building with gradle and importing into Android Studio.

So, I created a branch named 'source-build' which based on the 'master' branch.
On the 'source-build' branch, I modified the build.gradle files and some Java files,
so that we can build it via Gradle and Android Studio.



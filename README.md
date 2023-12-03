# Qt5.12.2-xcode15-patch
Fixes error parsing pro file for Qt 5.15.2 on Mac with Xcode 15 (macOS 14 Sonoma).

The error looks like this:
`qmake error: Project ERROR: failed to parse default search paths from compiler output`

## How to patch
Copy and replace file `toolchain.prf` from this repo to `<path to Qt>/5.15.2/<clang_64 or other>/mkspecs/features`

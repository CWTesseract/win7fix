# Cube World Compatibility DLLs for Win7_64.

This is collection of DLLs to fix compatibility for Windows 7 in Cube World.

Because XAudio2.8 requires Windows 8+, this replaces XAudio with [FAudio](https://github.com/FNA-XNA/FAudio), an open-source XAudio reimplementation that works across multiple operating system by using SDL2.

If you like this project, please consider sponsoring/supporting [FAudio](https://github.com/FNA-XNA/FAudio) and it's creator [`flibitijibibo`](https://github.com/flibitijibibo).

# Usage
1. Head over to the [releases](https://github.com/CWTesseract/win7fix/releases) page and download the latest zip file.
2. Extract the `.dll` files to your cube world directory, next to your `cubeworld.exe`.

# Changelog
* v1.1: Update FAudio to new version to fix the crash on exit. (Thanks to [@flibitijibibo](https://github.com/flibitijibibo))
* v1.0: Initial release

# Known Issues
* As of v1.1, there are no currently known issues.

# Where did these come from?

These DLL's are from the following sources:
* `FAudio.dll` & `XAudio2_8.dll` -> I built a win64 release build of
[FAudio](https://github.com/FNA-XNA/FAudio), licensed under zlib. At commit [`5fc2311f23`](https://github.com/FNA-XNA/FAudio/tree/5fc2311f23210c6dd901933f4379eaf9d8bbf800).

* `SDL2.dll` -> A win64 release build of [SDL2](https://www.libsdl.org/), licensed under zlib. Version 2.0.10.

* `XInput1_4.dll` -> The original DirectInput `XInput1_3.dll` file from Microsoft, but renamed to `XInput1_4.dll`. ( Cube World only uses the `XInputGetState` export so this works.)




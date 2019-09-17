# Cube World Beta Compatibility DLLs for Win7_64.

This is collection of DLLs to fix compatibility for Windows 7 in the Cube World Beta (0.9.1-0).

# Usage
1. Head over to the [releases](https://github.com/CWTesseract/win7fix/releases) page and download the zip file.
2. Extract the `.dll` files to your cube world directory, next to your `cubeworld.exe`.

# Where did these come from?

These DLL's are from the following sources:
* `FAudio.dll` & `XAudio2_8.dll` -> I built a win64 release build of
[FAudio](https://github.com/FNA-XNA/FAudio), an XAudio reimplementation, licensed under zlib.

* `SDL2.dll` -> A win64 release build of [SDL2](https://www.libsdl.org/), licensed under zlib.

* `XInput1_4.dll` -> The original DirectInput `XInput1_3.dll` file from Microsoft, but renamed to `XInput1_4.dll`. ( Cube World Beta 0.9.1-0 only uses the `XInputGetState` export so this works.)




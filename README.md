# Simple Tesseract Python Wrapper

Simple jupyter notebook example how to use tessseract library API in python with cffi.

This is not aim to replace any other solution python&tesseract - just nudge to improve current posibilities.


## Requirements

*  **tesseract** (and therefore **leptonica**) **libraries**:  in this example  I will use libraries created for Windows 64bit build as described "[Building tesseract and leptonica with CMake and Clang on Windows]( http://www.sk-spell.sk.cx/building-tesseract-and-leptonica-with-cmake-and-clang-on-windows)". You may need to adjust absolute path to libraries (abs_path) in [5] based on your settings/enviroment.
*  python (I used 64 bit Python 3.6.6) with jupyter (1.0.0), cffi (1.12.2), Pillow (5.3.0). Matplot (3.0.2) and numpy (1.16.1) are needed only for inline displaying of images in jupyter notebook.

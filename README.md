# alphasync (2024 ed.)

<img width="551" alt="Preview" src="https://github.com/rplacd/alphasync-2024/assets/147152/b3741b03-b1e4-4b79-9e78-c1603e44afad">

A desktop file manager for AlphaSmart NEO laptop devices connected to a Mac.

This is an alternative to the Neo Manager software from renaissance learning or to using the Neo's
keyboard emulation to transfer text files. It has the following advantages over Neo Manager:

- single-key backup of all text data (including named files, which are not accessible to Neo Manager)
- drag-and-drop text files to/from the Neo
- optional automatic application launch when a Neo device is connected to the host Mac
- automatic text conversion to/from MacASCII, UTF8 or UTF16 file formats

The application contains a build-in user-mode USB driver, requiring no driver install.

It is compatible with Macs, both Intel and Apple Silicon, running 10.13 onwards.

The project file is compatible with Xcode 15.

## Known bugs

The Inspector *sometimes* doesn't show AlphaWord file previews – falsely displaying nothing.

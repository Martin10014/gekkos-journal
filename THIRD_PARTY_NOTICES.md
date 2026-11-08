# Third-party software

Gekko’s Journal uses **Qt, PySide6 and Shiboken6 under LGPL version 3**. The application's own license does not restrict your rights to those libraries, including modifying/replacing compatible library builds and reverse engineering to debug those changes.

The Windows download includes license texts, copyright notices, third-party attributions and library replacement instructions in its `licenses` folder. The original Qt/PySide libraries are unmodified and are loaded dynamically.

For **version 0.1.4**, these corresponding source archives are available beside the application on the [release page](https://github.com/Martin10014/gekkos-journal/releases/tag/v0.1.4):

- `qtbase-everywhere-src-6.12.0.tar.xz`
- `qtsvg-everywhere-src-6.12.0.tar.xz`
- `qtimageformats-everywhere-src-6.12.0.tar.xz`
- `pyside-setup-everywhere-src-6.12.0.tar.xz` (includes PySide6 and Shiboken6)

The archives contain **third-party library source**, not Gekko’s Journal’s private application source. The download also includes a source manifest with upstream URLs and SHA-256 checksums.

Other bundled components include CPython 3.12.14 and the PyInstaller 6.22.3 bootloader/runtime, each under its own license. See the download for their complete terms and the notices for their dependencies. The optional voice helper uses Windows-installed .NET Framework and System.Speech; those Windows components are not bundled.

Gekko’s Journal is an unofficial Phasmophobia fan tool and is not affiliated with Kinetic Games. No game artwork, game audio or third-party cheat-sheet code is bundled.

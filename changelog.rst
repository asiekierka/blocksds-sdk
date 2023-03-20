##################
BlocksDS changelog
##################

Version 0.3.1 (2023-03-20)
==========================

- Hotfix.

Version 0.3 (2023-03-20)
========================

- FatFs performance improvements (like adding a disk cache).
- Support DLDI in the ARM7 as well as the ARM9.
- Add function for the ARM9 to request the ARM7 to read the cartridge.
- Add some missing definitions of DSi registers (SCFG/NDMA).
- General cleanup of libnds code (like replacing magic numbers by defines).
- Build system improvements (support two line app titles, remove old makefiles).
- libsysnds has been integrated in libnds.
- Bugfixes in libc and libnds.
  - EEPROM handling functions.
  - Data cache handling bugs.
  - Fix transparency in keyboard of libnds.
- Added some tests.

Version 0.2 (2023-03-15)
========================

- Improve C++ support (now the C++ standard library it is actually usable).
- Improve C library support.
- Integrate agbabi as ndsabi (provides fast memcpy, coroutines, etc).
- Fix install target.

Version 0.1 (2023-03-14)
========================

First beta release of BlocksDS. Features:

- Supports libnds, maxmod, dswifi.
- Supports a lot of the standard C library.
- Very early support of the standard C++ library.
- Supports DLDI, DSi SD slot and NitroFAT (open source alternative of NitroFS)
  through Elm's FatFs.
- Documentation on how to migrate projects to BlocksDS.
- Docker image provided.


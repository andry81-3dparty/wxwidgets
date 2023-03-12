* README_EN.txt
* 2023.03.12
* wxwidgets

1. DESCRIPTION
2. SOURCES
3. PATCHES
4. DEPENDENCIES
5. EXTERNALS
6. AUTHOR

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
`wxwidgets` library fork

-------------------------------------------------------------------------------
2. SOURCES
-------------------------------------------------------------------------------
https://www.wxwidgets.org/downloads/

-------------------------------------------------------------------------------
3. PATCHES
-------------------------------------------------------------------------------
The original library patched to fix these issues:

1. Build under Visual Studio 2015 Update 3 (Windows XP x86 SP2 target).
2. Turned everything off except build of wxFileDialog to minimize the output
   executable size.
3. Switched to build static libraries instead of dynamic.

-------------------------------------------------------------------------------
4. DEPENDENCIES
-------------------------------------------------------------------------------
N/A

-------------------------------------------------------------------------------
5. EXTERNALS
-------------------------------------------------------------------------------
To checkout externals you must use the
[vcstool](https://github.com/dirk-thomas/vcstool) python module.

NOTE:
  To install the module from the git repository:

  >
  python -m pip install git+https://github.com/dirk-thomas/vcstool

-------------------------------------------------------------------------------
6. AUTHOR
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)

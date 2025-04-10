# Put compiled help Files (CHMs) on display from Dyalog APL

## Overview

This class serves two simple purposes:

 * Display a help file, starting with the default topic.

 * Display a particular (named) topic in a particular help file

You must create an instance before you can use the methods the class is coming with, and you must make sure that the Destructor is called at some point because otherwise APL might crash. This is neither a fault of the class nor of APL, it's simply how the underlying DLL is defined.

You can get details about how to use `ShowChmHelp` with the user command ADOC; execute:

```
      ]ADOC.Browse #.ShowChmHelp
```

## Installation

In order to try it out:

```
]LoadPackages [tatin]ShowChmHelp
```

Use `]InstallPakages`  for installing the package for long-term usage.

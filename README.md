# Put help Files (CHMs) on display from Dyalog APL


`ShowChmHelp` is a member of the APLTree library. The library is a collection of classes etc. that aim to support the Dyalog APL programmer. Search GitHub for "apltree" and you will find solutions to many every-day problems Dyalog APL programmers might have to solve.


## Overview

This class serves two simple purposes:

 * Display a help file, starting with the default topic.

 * Display a particular (named) topic in a particular help file

You must create an instance before you can use the methods the class is coming with, and you must make sure that the Destructor is called at some point because otherwise APL might crash. This is neither a fault of the class nor of APL, it's simply how the underlying DLL is defined.

You can get details about how to use `ShowChmHelp` with the user command ADOC; execute:

```
      ]ADOC.Browse #.ShowChmHelp
```
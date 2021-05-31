# Building gpp for windows

If you don't already have the Visual Studio IDE or build tools, install the build tools from https://visualstudio.microsoft.com/downloads/#build-tools-for-visual-studio-2019

Open a developer command prompt from the windows start menu - for me it is under the "Visual Studio 2019" folder.

Navigate to this directory in the command window, then execute the following cl command, which should generate output as shown.

```
> cl -DHAVE_CONFIG_H -I. ..\src\gpp.c
Microsoft (R) C/C++ Optimizing Compiler Version 19.29.30037 for x86
Copyright (C) Microsoft Corporation.  All rights reserved.

gpp.c
Microsoft (R) Incremental Linker Version 14.29.30037.0
Copyright (C) Microsoft Corporation.  All rights reserved.

/out:gpp.exe
gpp.obj
```

# DIE .See https://github.com/OpenSrceng

# Source SDK 2012

## support game(s)
* Counter-Strike: Global Offensive
* ~~Left 4 Dead~~
* ~~Portal 2~~
* ~~Alien Swarm~~

## Build
### Linux:

dependencies:
fontconfig, freetype2, SDL2, libcurl

Build:

0) Examine which build options are available: `./waf --help`
1) Configure build: `./waf configure -T release`
2) Install: `./waf install`

### ANDROID:

dependencies:
[Android ndk (r10-r13)](https://github.com/android/ndk/wiki/Unsupported-Downloads), [clang11](https://github.com/llvm/llvm-project/releases/download/llvmorg-11.1.0/clang+llvm-11.1.0-x86_64-linux-gnu-ubuntu-16.04.tar.xz)

Build:

0) export ANDROID_NDK_HOME="PATH/TO/NDK/android-ndk-r10e" and export PATH="PATH/TO/CLANG/bin:$PATH"
1) Examine which build options are available: `./waf --help`
2) Configure build: `./waf configure -T release --togles --android=aarch64,host,21`
3) Install: `./waf install`

               SOURCE 1 SDK LICENSE

Source SDK Copyright(c) Valve Corp.  

THIS DOCUMENT DESCRIBES A CONTRACT BETWEEN YOU AND VALVE 
CORPORATION ("Valve").  PLEASE READ IT BEFORE DOWNLOADING OR USING 
THE SOURCE ENGINE SDK ("SDK"). BY DOWNLOADING AND/OR USING THE 
SOURCE ENGINE SDK YOU ACCEPT THIS LICENSE. IF YOU DO NOT AGREE TO 
THE TERMS OF THIS LICENSE PLEASE DON’T DOWNLOAD OR USE THE SDK.  

  You may, free of charge, download and use the SDK to develop a modified Valve game 
running on the Source engine.  You may distribute your modified Valve game in source and 
object code form, but only for free. Terms of use for Valve games are found in the Steam 
Subscriber Agreement located here: http://store.steampowered.com/subscriber_agreement/ 

  You may copy, modify, and distribute the SDK and any modifications you make to the 
SDK in source and object code form, but only for free.  Any distribution of this SDK must 
include this LICENSE file and thirdpartylegalnotices.txt.  
 
  Any distribution of the SDK or a substantial portion of the SDK must include the above 
copyright notice and the following: 

    DISCLAIMER OF WARRANTIES.  THE SOURCE SDK AND ANY 
    OTHER MATERIAL DOWNLOADED BY LICENSEE IS PROVIDED 
    "AS IS".  VALVE AND ITS SUPPLIERS DISCLAIM ALL 
    WARRANTIES WITH RESPECT TO THE SDK, EITHER EXPRESS 
    OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, IMPLIED 
    WARRANTIES OF MERCHANTABILITY, NON-INFRINGEMENT, 
    TITLE AND FITNESS FOR A PARTICULAR PURPOSE.  

    LIMITATION OF LIABILITY.  IN NO EVENT SHALL VALVE OR 
    ITS SUPPLIERS BE LIABLE FOR ANY SPECIAL, INCIDENTAL, 
    INDIRECT, OR CONSEQUENTIAL DAMAGES WHATSOEVER 
    (INCLUDING, WITHOUT LIMITATION, DAMAGES FOR LOSS OF 
    BUSINESS PROFITS, BUSINESS INTERRUPTION, LOSS OF 
    BUSINESS INFORMATION, OR ANY OTHER PECUNIARY LOSS) 
    ARISING OUT OF THE USE OF OR INABILITY TO USE THE 
    ENGINE AND/OR THE SDK, EVEN IF VALVE HAS BEEN 
    ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.  
 
       
If you would like to use the SDK for a commercial purpose, please contact Valve at 
sourceengine@valvesoftware.com.

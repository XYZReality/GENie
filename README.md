GENie - Project generator tool (XYZ Reality fork)
=================================================

What is it?
-----------

**GENie** (pronounced as Jenny) is a third-party project generator tool, making applying the same settings for
multiple projects easy.

Note: This is the **XYZ Reality's** forked and customized version of GENie, added
Linux on ARM architecture support to be able to build projects on nVidia Orin board.
For the original repo readme please go to: https://github.com/XYZReality/GENie/Original_README.md

Building
--------
**Important Note:** You normally don't need to build this tool as it is only for internal development, used in some repos
to generate multi-platform project files (e.g. for bgfx, bx, bimg). The pre-built binaries of this tool as well as 
the project files for all desired platforms based on this tool are already generated and added to our corresponding 
customized library repos.<br>

But in case you need to rebuild this tool for any reason, please follow the instructions here:

**Windows:**
```
1- Clone the repo to some folder
2- Open the visual studio solution file from GENie/scripts/genie.sln
3- Build
```
Running this tool under Windows doesn't give you too much since it is mainly targeted for Linux. <br><br>
**Linux:**
```
$ git clone https://github.com/XYZReality/GENie.git
$ cd GENie
$ make
```
Based on the CPU architecture of the machine you are building this on, it will generate the binaries in either GENie/bin/linux or
GENie/bin/linux-arm accordingly.

[License](https://github.com/bkaradzic/genie/blob/master/LICENSE)
-----------------------------------------------------------------

	GENie
	Copyright (c) 2014-2018 Branimir Karadžić, Neil Richardson, Mike Popoloski,
	Drew Solomon, Ted de Munnik, Miodrag Milanović, Brett Vickers, Bill Freist,
	Terry Hendrix II, Ryan Juckett, Andrew Johnson, Johan Sköld,
	Alastair Murray, Patrick Munns, Jan-Eric Duden, Phil Stevens, Stuart Carnie,
	Nikolay Aleksiev, Jon Olson, Mike Fitzgerald, Anders Stenberg, Violets,
	Hugo Amnov, Christian Helmich.
	All rights reserved.

	https://github.com/bkaradzic/genie
	
	Redistribution and use in source and binary forms, with or without modification,
	are permitted provided that the following conditions are met:
	
	1. Redistributions of source code must retain the above copyright notice,
		this list of conditions and the following disclaimer.
	
	2. Redistributions in binary form must reproduce the above copyright notice,
		this list of conditions and the following disclaimer in the documentation
		and/or other materials provided with the distribution.
	
	3. Neither the name of the GENie nor the names of its contributors may be 
		used to endorse or promote products derived from this software without
		specific prior written permission.
	
	THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
	ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
	WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE 
	DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
	FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
	DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
	SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
	CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
	OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
	OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

  [jcdb]: https://clang.llvm.org/docs/JSONCompilationDatabase.html
  [zbs]: https://studio.zerobrane.com

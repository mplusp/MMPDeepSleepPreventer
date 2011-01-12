Description:
	MMPDeepSleepPreventer is an Objective-C class used to prevent iOS devices from deep sleeping.
	This has been tested on an iOS versions 3.0 to 4.2.1, so far and should work on all devices,
	running one of these iOS versions.
	
	MMPDeepSleepPreventer is released under the New BSD License. (Below is the exact license text).
	If you use this code a little attribution note would be greatly appreciated.


How-To Use:
	- Add MMPDeepSleepPreventer.h and MMPDeepSleepPreventer.m as well as
	  MMPSilence.wav to your project.
	- Add “AVFoundation.framework” and “AudioToolbox.framework” to your project.
	- Import MMPDeepSleepPreventer.h where you want to use the class.
	- Instantiate an MMPDeepSleepPreventer object.
	- Use -[MMPDeepSleepPreventer startPreventSleep]
	  and -[MMPDeepSleepPreventer stopPreventSleep] when needed.


Inspired by:
	Some question on stackoverflow.com
	Some posts on Apple's devforums.


License:
Copyright (c) 2009-2011, Marco Peluso - marcopeluso.com
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

  1. Redistributions of source code must retain the above copyright notice,
     this list of conditions and the following disclaimer.

  2. Redistributions in binary form must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  3. Neither the name of the copyright holders nor the names of its
     contributors may be used to endorse or promote products derived from
     this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR
CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF
ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

# chess
chess with using olcPixelGameEngine


Compiling in Linux
	~~~~~~~~~~~~~~~~~~
	You will need a modern C++ compiler, so update yours!
  To compile with Makefile just use: 
  
	make

	On some Linux configurations, the frame rate is locked to the refresh
	rate of the monitor. This engine tries to unlock it but may not be
	able to, in which case try launching your program like this:

	vblank_mode=0 ./YourProgName


Compiling in Window
	~~~~~~~~~~~~~~~~~~
You will need just distribute all files into MVS without Makefile

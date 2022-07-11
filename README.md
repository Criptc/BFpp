# BFpp
BrainFuck++, adds 3 new commands #, reads the tape from the current postion untill a 0, then uses that to open a file. If file is already open, it will close it
:, reads a character from the open file, puts it in the current tape postion and advances the pointer
;, reads the tape untill a 0, then writes that to the file (will only write when the file gets closed)

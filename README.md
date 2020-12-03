6SV-2.1 Second Simulation of a Satellite Signal in the Solar Spectrum, Vector, version 2.1.

6sV-2.1.tar: a tar-file with a source code (FORTRAN 95).
The code works under Unix.


To unpack the tar-file, type: tar -xvf 6sV-2.1.tar
Makefile should be in the same directory as the code.

To compile the code (to create an executable file), type: make
You should see object files *.o and the executable sixsV2.1.

To run the code, type: ./sixsV2.1 <input_file_name >output_file_name
Or, if you want to see your results on the screen, type: 
./sixsV2.1 <input_file_name

 
At our 6SV Web site (http://6S.ltdri.org), we provide a special Interface which can help an unexperienced user learn how to create necessary input files. We also provide four files with example inputs (created with the help of the Interface) and outputs. They are in the 'Examples' directory.


If you need more angles for computations, copy paramdef.inc-highaccuracy as
paramdef.inc, if not use paramdef.inc-normalaccuracy






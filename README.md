# Modified-S-UNIWARD-Implementation
A modified version of the S-UNIWARD implementation that can be found at https://dde.binghamton.edu/download/stego_algorithms/

The original implementation simulates embedding encrypted data by generating random bits. This version has been modified to embed a specified payload.
The original requires a directory of cover images as an input. This version will accept a directory or a single image as an input. 
The project requires the boost library which I did not upload. It can be downloaded from https://www.boost.org/ and compiled using the script provided.
The lib folder contains object files for some of the boost library functions. It was compiled using the vc143 toolset.
If you are compiling this with a different toolset you will need to replace these files with versions compiled using your toolset version.
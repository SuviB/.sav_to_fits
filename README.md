# .sav_to_fits
Project in the Magnetic_connectivityrepository saves an IDL structure wih the PFSS model and a few other things in a .sav file. 
This code reads the .sav files from the zipped folders and saves them into .fits (Flexible Image Transport System). 

Problem: cannot open the .sav file if it is too large for your RAM, which it sometimes can be if you've traced i.e. 
10^6 field lines.

Solved: pfss.pro does not save the closed field lines anymore, so normally the files should be of a reasonable size.

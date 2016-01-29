#          FAKEFETCH 1.0          #
The most plebeian screenfetch clone in existence       

-------------CONTENTS------------
 1. Introduction
 2. Picking the right version    
 3. Configuring fakefetch        
 4. Using fakefetch              

1. |        INTRODUCTION         

Fakefetch is a primitive bash script designed to provide the hardware and software configuration information of your UNIX 
system in a more "aesthetically pleasing" format. Fakefetch is intended for use primarily in screenshots or to provide 
system configuration information to remote users on your system. All system information (exempting your hostname and shell) 
are entered manually.

 2. | PICKING THE RIGHT VERSION   

**Fakefetch is currently only geared towards Solaris, however HP-UX and AIX versions are planned.

"Headless" systems accessed solely through SSH or console should use the fakefetch-h script, which comes in three flavors:
fakefetch-hm: Colorless version for monochrome serial "dumb" terminals or terminal emulators with no color support.
fakefetch-h16: 16-color version for color serial "dumb" terminals or terminal emulators that do not support 256 colors.
fakefetch-hc: 256-color version for terminal emulators that support 256 color output.

As of 28 January 2016, fakefetch-d for desktop/workstation systems is still in development.

 3. |    CONFIGURING FAKEFETCH    

Fakefetch presents all configurable variables in a block at the top of the script, simply replace the template specs with 
your own and you're good to go.

 4. |       USING FAKEFETCH       

After you are finished entering in your hardware configuration, make sure the script is executable by typing "chmod +x 
[fakefetch version]"

If you plan on only using a single version of fakefetch, you may find it more convenient to remove the version suffix and 
place it in a directory in your $PATH.

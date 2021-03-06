SGDK 1.4 (mai 2019)
Copyright 2019 Stephane Dallongeville
https://github.com/Stephane-D/SGDK

SGDK is an open and free development kit for the Sega Megadrive.
It contains the development library itself (with the code sources) and some custom tools used to compile resources.
SGDK uses the GCC compiler (m68k-elf target) and the libgcc to generate ROM image. Binaries (GCC 6.3) are provided for Windows OS for convenience but you need to install it by yourself for others operating systems.
Note that SGDK also requires Java (custom tools need it) so you need to have Java JRE installed on your system:
https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html

SGDK library and custom tools are distributed under the MIT license (see license.txt file).
GCC compiler and libgcc are under GNU license (GPL3) and any software build from it (as the SGDK library) is under the GCC runtime library exception license (see COPYING.RUNTIME file)

You can find installation instructions and basic tutorials about how use SGDK on this page:
https://github.com/Stephane-D/SGDK/wiki

WARNING: tutorials available in wiki pages are unfortunately terribly outdated :-/
Sorry for that, i plan to update them in future but in the meantime i strongly suggest you to have a look on the available samples instead in the 'sample' directory of SGDK.
The 'sprite' example is particularly useful as it show the basics in a small example.

You can also use the SGDK library doxygen documentation in the 'doc' directory: doc/html/files.html

Unix/Linux users should give a try to the Gendev project from Kubilus:
https://github.com/kubilus1/gendev
It allows to quickly setup SGDK on a Unix environment.

MacOSX users also have access to SGDK with Gendev for MacOS from Sonic3D:
https://github.com/SONIC3D/gendev-macos

There is also the new and nice solution proposed by Daniel Valdivieso tu use SGDK under any OS using Wine: 
https://github.com/v4ld3r5/sgdk_vscode_template

If you enjoy SGDK you can now support it on Patreon or using the Paypal donation link :)
https://www.patreon.com/SGDK
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2SCWVXYDEEBUU

Thanks =) I wish you a happy coding time !
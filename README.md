# operating_systems
This repo is for my deep understanding of operating systems and what each one can do.


Book: 
https://download-mirror.savannah.gnu.org/releases/pgubook/ProgrammingGroundUp-1-0-booksize.pdf


--Using Linux Mint

##Packages Installed:
 apt install qemu
 apt install nasm
 apt install make
##Usefull Commands:
###To compile:
nasm -f bin "filename".asm -o "filename".bin

###To run the code:
qemu-system-x86_64 "filename".bin qemu "filename".bin

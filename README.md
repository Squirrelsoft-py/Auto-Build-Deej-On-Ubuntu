# Auto-Build-Deej-On-Ubuntu
An automated way to build deej on Ubuntu

## Usage
1. Put "compile" into the folder, where the deej folder will be created.
2. Open the terminal, navigate to the file and give the script execution permissions with: 'chmod +x compile'
3. execute with ./compile
4. Now it should do everything by itself
5. Start deej with './deej' - remember that the 'config.yaml' file should always be in the same folder as the main program

## But why did I write this?
The libraries deej uses are all very old. This is why they can't be installed easily. So the new versions are used and symlinks are created to point the program to the new libraries. 
Added bonus:
- Auto configure the COM port
- allows user to access deej as a serial device, else deej can't work

# Doesn't work? Message me on https://infosec.exchange/@squirrelsoft

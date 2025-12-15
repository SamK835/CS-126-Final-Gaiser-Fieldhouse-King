# CS-126-Final-Gaiser-Fieldhouse-King
# mini-Unix-Shell

## authors
**Names:** Samuel Gaiser, Kaden Fieldhouse, Samuel King
**Course:** CS 12600-001 Systems Programming In C
**Semester:** Fall 2025
___________________________________________________________________________________

## Build Instructions
myShell must be built using a linux system or WSL through windows powershell.

## Run Instructions
Step 1: Open Windows Terminal or Powershell<br/>
Step 2: Type the "wsl" command to run the linux virtual machine <br/>
Step 3: Navigate to the project folder <br/>
    example: cd /mnt/c/Users/<YourUserName>/Documents/"C Final Project" <br/>
Step 4: Type "make" command to build the shell <br/>
Step 5: To run shell type "./myshell" <br/>
Step 6: You will see a prompt that says "myshell>", once this appears, you can utilize the mini shell. <br/>

## Sample Code To Try
ls <br/>
ls -l <br/>
ls -l > outfile.txt <br/>
cat < outfile.txt <br/>
sleep 10 <br/>
cd <br/>
ls | ws -l <br/>
_______________________________________________________________________________

## Known Limitations
The only known limitation as of right now is that the shell will not run outside of a linux environment, this means that windows terminal or WSL in powershell

DES-ECB Encrytion/Decryption
-------------------------------------------

DES encryption is located in the des directory under the root directory
The key is named deskey.txt
The output from my commands using DES is in the des/output directory.

Each folder has a makefile. To compile the code, simply run the make command.
To delete output files and compiled files, run make clean.

To encrypt a file using DES:
 > ./DES_ECB_Enc -k deskey.txt -i CS468-HW2.txt -o CS468-HW2.mydesecb

To decrypt a file using DES:
 > ./DES_ECB_Dec -k deskey.txt -i CS468-HW2.mydesecb -o CS468-HW2-mydesecb.txt

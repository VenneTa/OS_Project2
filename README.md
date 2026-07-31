# OS_Project2
Project 2 for the OS course

This project really consisted of 4 mini projects. Each created a simple UNIX utility function.

The first sub project was to create a copy of the cat functionality called my-cat. cat is a functionality that allows showcasing files to the terminal. It is run like "./my-cat file1 file2 ... fileN" for N many files you want to showcase. 

The second sub project was to create a copy of grep functionality called my-grep. If my-grep takes in both a string and a file, it is run like "./my-grep string file1 ... fileN". If it only takes in a string it is run like "./my-grep string".

The third mini project was to create a C program that does run length encoding to a text file and changes the format to a 4-byte integer binary. my-zip is run like "./my-zip file1.txt file2.txt ... fileN.txt $>$ file.bin", where N is the amount of text files encoded and compressed to a single 4 byte binary file.

The fourth mini project was to create a C program that decodes the result of the my-zip functionality, returning a run length encoded 4-byte integer binary file into a text file. my-unzip is run like "./my-unzip file1.bin file2.bin ... fileN.bin $>$ file.txt", where N is the amount of files decoded into a single text file.

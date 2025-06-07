# CYBR 5330-001-Data Carver and Password Cracker


For this project, we wrote an Automatic Data Carver Program using Python. We used the following
libraries for the same - sys, re, os, hashlib. The program asks the user to enter a file through the
command line which is to be carved. It is assumed that the file will be a binary file. Two
dictionaries are created for storing SOF and EOF signatures for JPEG/JPG, PNG and PDF files.
Once the user enters the file, the program searches for Start of File (SOF) and End of File (EOF)
offsets and stores them in lists. There are separate lists for SOF and EOF offsets according to the
file types. Once we get the SOF and EOF offsets for the above file types, we carve the files and
store it in the following format - ‘carved_1.jpeg’, ‘carved_2.png’, ‘carved_3.pdf’, etc. The
program is tested on ‘midterm.dd’ and 'carve.lab' files. MD5 hash of all the carved files is also
calculated to check if the files carved by the program match the files carved manually. The program
outputs basic file information like the file name, file type, SOF and EOF offsets in bytes, File size
and the MD5 hash of the file. The MD5 hashes are also stored in a file called ‘hashes.txt’. All the
carved files and the file ‘hashes.txt’ are stored in a directory titled by my last name ”Nellore
Prasad”. The output is attached below

1)Roshan Nellore Prasad
2)Shefali Athavale

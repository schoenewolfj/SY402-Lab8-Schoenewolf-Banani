# SY402-Lab8-Schoenewolf-Banani
Recursively hashing all files on a machine.

YOU WILL NEED TO HAVE A PATH "/etc/lab8" IN ORDER TO EXECUTE THIS CODE
  
The first time running this code, all files on a system will be hashed and stored at location "/etc/lab8/part2output.txt".  If run a second time, all files will be hashed again.  This time, if there are any changes or additional files that have been hashed, they will be added to the part2output.txt.  These changes in hashes will also be printed to standard output.

In addition to the part2output.txt file, files "part3output.txt" and "updatedlist.txt" will also be created.  "part3output.txt" will contain the readable hashes of the new/modified hashes that occur from the first hash instance to the second.  "updatedlist.txt" will contain the filepath, file, read able hash, and a timestamp of the new/modified hashes that occur from the first hash isntance to the second.

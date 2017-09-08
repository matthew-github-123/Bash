# Bash

- Bash Shell Script
- Receives a password file as input via STDIN
- Password file will be of the form username:passwordhash (contains multiple lines)

- Script guesses the cleartext that corresponds to the password hash
- Part A looks for common passwords for each password hash
- Part B attemps a dictionary attack for each password hash (the dictionary should be named 'words' and be in the same folder as Script18)
- Part C attempts a brute force attack against the password hashes

- For every password found, the script will print out the corresponding username and cleartext

- In order to run open up linux terminal and run ./script18 passwordfile.txt
- passwordfile.txt is your own password file and is not included
- There should also be a corresponding dictionary named 'words' in the same folder (however this is also not included)

# SSH-Bruteforce

## Introduction
A brute-force attack on SSH connection using Python Script.

## Commands
* To run :- ``` Python3 ssh_cracker.py [IP Address] -u [User Name] -P wordlist.txt```
### Make sure your ip address has active ssh connection. ###
* To install require modules :- ``` pip3 install -r requirements.txt ```
* To see the usage :- ``` Python3 ssh_cracker.py --help ```
### Output
``` 
usage: bruteforce_ssh.py [-h] [-P PASSLIST] [-u USER] host

SSH Bruteforce Python script.

positional arguments:
host                  Hostname or IP Address of SSH Server to bruteforce.

optional arguments:
-h, --help            show this help message and exit
-P PASSLIST, --passlist PASSLIST
                        File that contain password list in each line.
-u USER, --user USER  Host username.
```

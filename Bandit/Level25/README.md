# Bandit Level 25 → Level 26

## Objective
Log into bandit26 using a private SSH key and escape from the restricted shell to retrieve the next level’s password.

## Procedure
1. Logged into bandit25.
2. Displayed and copied the private SSH key from the server.
3. Pasted the key into a local file on the terminal.
4. Changed the key file permissions to make it usable for SSH.
5. Logged into bandit26 using the private key.
6. Identified that the default shell was restricted.
7. Escaped the restricted shell.
8. Accessed the password for the next level.

## Commands Used
- cat
- chmod
- ssh
- vi

## Result
Successfully authenticated using the private key, escaped the restricted shell, and retrieved the password for the next level.

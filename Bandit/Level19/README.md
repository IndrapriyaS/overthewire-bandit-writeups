# Bandit Level 19 → Level 20

## Objective
Use the setuid binary in the home directory to access the password stored in `/etc/bandit_pass`.

## Procedure
1. Logged into the current Bandit level.
2. Identified the setuid binary located in the home directory.
3. Executed the binary without arguments to understand its usage.
4. Used the binary to run a command with elevated privileges.
5. Read the password file from `/etc/bandit_pass`.

## Commands Used
- ls
- ./bandit20-do
- cat

## Result
The password for the next level was successfully retrieved from `/etc/bandit_pass`.

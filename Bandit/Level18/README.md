# Bandit Level 18 → Level 19

## Objective
Retrieve the password stored in the file `readme` from the home directory, despite being logged out automatically due to a modified `.bashrc`.

## Procedure
1. Connected to the Bandit server using SSH while bypassing the default shell behavior.
2. Executed a command directly during login instead of opening an interactive shell.
3. Read the contents of the `readme` file in the home directory.

## Commands Used
- ssh
- cat

## Result
The contents of the `readme` file revealed the password for the next level.

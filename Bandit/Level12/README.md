# Bandit Level 12 → Level 13

## Objective
Retrieve the password required to advance to the next level.

## Procedure
1. Connected to the Bandit server using SSH.
2. Created a temporary working directory under `/tmp`.
3. Copied the `data.txt` file into the working directory.
4. Converted the hexdump back into its original binary form.
5. Identified the type of compression used on the file.
6. Repeatedly decompressed the file until the original content was obtained.
7. Read the final output to retrieve the password.

## Commands Used
- ssh
- mktemp
- cp
- mv
- xxd
- file
- gzip / bzip2 / tar
- cat

## Result
The password for the next level was successfully retrieved.

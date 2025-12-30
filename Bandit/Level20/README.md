# Bandit Level 20 → Level 21

## Objective
Use the setuid binary to authenticate by sending the current level’s password to a local port and receive the password for the next level.

## Procedure
1. Logged into the current Bandit level.
2. Identified the setuid binary in the home directory.
3. Started a listener on localhost on a chosen port.
4. Executed the setuid binary with the chosen port as an argument.
5. Sent the current level’s password through the connection.
6. Received the password for the next level upon successful verification.

## Commands Used
- ls
- nc
- ./suconnect

## Result
The setuid binary validated the password and returned the credentials for the next level.

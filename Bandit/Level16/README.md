# Bandit Level 16 → Level 17

## Objective
Retrieve the next level credentials by identifying the correct service running on localhost within the port range 31000–32000.

## Procedure
1. Logged into the current Bandit level.
2. Scanned the specified port range to identify which ports had active servers listening.
3. Tested the open ports to determine which ones used SSL/TLS encryption.
4. Sent the current level password to the identified SSL/TLS-enabled service.
5. Received the credentials for the next level from the correct server.

## Commands Used
- nmap
- openssl s_client
- nc

## Result
Successfully identified the correct SSL/TLS service and retrieved the next level credentials.

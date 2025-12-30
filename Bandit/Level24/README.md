# Bandit Level 24 → Level 25

## Objective
Retrieve the next level’s password by brute-forcing a 4-digit pincode and submitting it along with the current password to a service running on port 30002.

## Procedure
1. Logged into the current Bandit level.
2. Identified that a daemon is listening on port 30002.
3. Prepared the current level’s password.
4. Brute-forced all possible 4-digit numeric pincodes (0000–9999).
5. Sent the password and each pincode through a single persistent connection.
6. Identified the correct pincode from the successful response.
7. Retrieved the password for the next level.

## Commands Used
- nc
- echo
- for loop
- bash

## Result
After brute-forcing all combinations, the correct pincode was found and the daemon returned the password for the next level.

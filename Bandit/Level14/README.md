# Bandit Level 14 → Level 15

## Objective
Retrieve the next level password by submitting the current level password to a service running on localhost.

## Procedure
1. Logged into the current Bandit level.
2. Identified that a service was listening on port 30000 of localhost.
3. Sent the current level password to the specified port.
4. Received the password for the next level as a response.

## Commands Used
- nc
- echo

## Result
Successfully retrieved the password for the next level by communicating with the local service.

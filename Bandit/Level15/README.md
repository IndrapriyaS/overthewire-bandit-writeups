# Bandit Level 15 → Level 16

## Objective
Retrieve the next level password by securely submitting the current level password to a service using SSL/TLS encryption.

## Procedure
1. Logged into the current Bandit level.
2. Identified that the service on localhost requires an encrypted connection on port 30001.
3. Established an SSL/TLS connection to the specified port.
4. Submitted the current level password through the secure channel.
5. Received the password for the next level as a response.

## Commands Used
- openssl s_client
- echo

## Result
Successfully retrieved the next level password via an SSL/TLS‑encrypted connection.

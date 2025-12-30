# Bandit Level 21 → Level 22

## Objective
Identify the command executed by a cron job and locate where the next level’s password is stored.

## Procedure
1. Logged into the current Bandit level.
2. Navigated to the cron configuration directory.
3. Identified the cron job related to the Bandit level.
4. Examined the script executed by the cron job.
5. Traced the script logic to find where it reads the password.
6. Retrieved the password for the next level from the referenced location.

## Commands Used
- cd /etc/cron.d
- ls
- cat
- bash

## Result
The cron job revealed the command being executed, leading to the location of the next level’s password.

# Bandit Level 23 → Level 24

## Objective
Inspect the cron job configuration to identify the command being executed and determine how the next level’s password can be obtained.

## Procedure
1. Logged into the current Bandit level.
2. Navigated to `/etc/cron.d/` to review cron job configurations.
3. Identified the cron job associated with this level.
4. Examined the script executed by the cron job.
5. Analyzed how the script handles password generation or storage.
6. Retrieved the password for the next level from the appropriate location.

## Commands Used
- cd /etc/cron.d
- ls
- cat
- bash

## Result
The cron job analysis revealed the process used to generate and store the next level’s password.

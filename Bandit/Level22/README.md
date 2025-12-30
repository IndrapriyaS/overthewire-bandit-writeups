# Bandit Level 22 → Level 23

## Objective
Analyze a cron job configuration to identify the command being executed and determine how it reveals the next level’s password.

## Procedure
1. Logged into the current Bandit level.
2. Navigated to the cron configuration directory.
3. Identified the cron job related to this level.
4. Examined the command executed by the cron job.
5. Analyzed the script to understand how the password is generated.
6. Located and retrieved the password for the next level.

## Commands Used
- cd /etc/cron.d
- ls
- cat
- bash

## Result
The cron job execution revealed the mechanism used to store the next level’s password.

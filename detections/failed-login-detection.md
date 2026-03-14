# Failed Login Detection

## Description
Detect multiple failed login attempts that may indicate a brute force attack.

## Detection Logic
Trigger alert if:

- More than 5 failed logins
- From the same IP address
- Within 2 minutes

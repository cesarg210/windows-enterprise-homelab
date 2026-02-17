# Account Lockout Policy Configuration

## Objective
Mitigate brute-force authentication attacks by enforcing account lockout controls.

## Lockout Settings Configured

- Account lockout threshold: 3 attempts
- Lockout duration: 15 minutes
- Reset counter after: 15 minutes

## Lockout Event Observed

- Event ID 4625 → Account locked out

## Evidence

![Lockout Policy Configured](../screenshots/35-account-lockout-settings.png)

![Account Locked Message](../screenshots/37-account-locked-message.png)

![Event 4625](../screenshots/38-account-lockout-event.png)

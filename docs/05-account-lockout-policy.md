# Account Lockout Policy Configuration

## Objective
Mitigate brute-force authentication attacks by enforcing account lockout controls.

## Lockout Settings Configured

- Account lockout threshold: 3 attempts
- Lockout duration: 15 minutes
- Reset counter after: 15 minutes

## Security Impact

Prevents:
- Automated password guessing
- Credential stuffing attempts

Creates:
- Defensive barrier
- Logged lockout events for detection

## Lockout Event Observed

- Event ID 4740 → Account locked out

## Evidence

![Lockout Policy Configured](../screenshots/10-account-lockout-policy-configured.png)

![Account Locked Message](../screenshots/11-account-locked-message.png)

![Event 4740](../screenshots/12-event-4740-account-locked.png)

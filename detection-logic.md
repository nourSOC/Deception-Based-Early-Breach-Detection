# Detection Logic

The detection approach is based on behavior-driven signals rather than traditional signature-based alerts.

## 1. Canary Tokens – Early Detection

Canary tokens are placed in locations that should never be accessed during normal operations.

Examples:

- Decoy files
- Fake credential artifacts
- Hidden directories

Any interaction with these resources immediately generates a high-confidence alert.

## 2. Lateral Movement Traps

Attackers often attempt to move laterally after gaining initial access.

Decoy network paths and resources are introduced to detect:

- Unauthorized access attempts
- Suspicious authentication activity
- Enumeration of network shares

These interactions act as strong indicators of malicious intent.

## 3. Behavioral Correlation

Detection signals can be correlated with additional telemetry such as:

- Process creation events
- PowerShell activity
- Authentication logs

This approach helps confirm malicious behavior while reducing false positives.

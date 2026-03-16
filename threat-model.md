# Threat Model

This project assumes a realistic internal attack scenario where an attacker has already gained an initial foothold inside the network.

The attacker may have obtained:

- Valid user credentials
- A compromised workstation
- Access through phishing or credential reuse

## Expected Attacker Behavior

Once inside the network, attackers typically perform the following actions:

- File and directory enumeration
- Searching for sensitive data
- Credential harvesting
- Lateral movement across hosts
- Persistence establishment

Traditional detection often occurs only after these stages.

This project focuses on identifying attacker behavior during the earliest possible stage of intrusion.

## Detection Philosophy

Instead of relying solely on alert-based monitoring, the goal is to introduce controlled deception elements that encourage attackers to reveal themselves.

These deception triggers generate high-confidence signals that can be investigated by SOC analysts.

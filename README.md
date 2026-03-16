# Early Breach Detection using Deception

This project explores a lightweight deception-based detection model designed to identify attackers during the earliest stages of intrusion.

Instead of relying on traditional alert-heavy monitoring, this approach focuses on forcing attackers to reveal their presence through controlled deception mechanisms.

## Core Idea

Most environments detect attackers only after:

- lateral movement
- access to internal resources
- persistence establishment

At that stage, incident response often requires disruptive actions such as full host isolation.

This project proposes a different approach:

Early Breach Detection & Smart Containment using Deception.

## Detection Approach

1. Canary Tokens — Early Foothold Detection
2. Lateral Movement Traps — Intent Validation
3. Service-Level Containment — Minimal Business Impact

## Objectives

- Detect attackers at the initial foothold stage
- Reduce false positives
- Confirm lateral movement with high confidence
- Contain threats without disrupting production

## Scope

- Windows environments
- Internal attacker scenarios
- SOC analyst–driven investigations
- MITRE ATT&CK aligned detection logic

## Documentation

Full technical explanation available in:

Defensive-based-Deception.pdf

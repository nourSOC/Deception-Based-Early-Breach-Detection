# Containment Strategy

Traditional incident response often relies on aggressive containment strategies such as:

- Full host isolation
- Network disconnection
- Immediate shutdown

While effective, these actions can have significant business impact.

## Smart Containment Approach

This project proposes a more controlled containment model.

### Service-Level Containment

Instead of isolating the entire host, response actions may include:

- Restricting specific services
- Blocking suspicious processes
- Monitoring attacker activity in a controlled environment

This allows security teams to:

- Gather more intelligence about the attacker
- Confirm malicious intent
- Reduce operational disruption

## SOC Analyst Decision Model

Alerts generated through deception triggers should be reviewed by SOC analysts who can determine the appropriate response level.

This ensures that containment actions are both effective and proportional to the threat.

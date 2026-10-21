# Triage Runbook

## Escalation ladder

1. First responder confirms the alert is actionable and acknowledges it in the incident channel.
2. If triage takes longer than 15 minutes, escalate to the primary on-call engineer.
3. If the primary on-call cannot resolve the incident within 30 minutes, escalate to the secondary on-call engineer.
4. If the incident is still unresolved, escalate to the engineering manager on duty.
5. For customer-impacting outages, page the platform lead and open a status page incident.

## After-hours paging

If an alert fires outside business hours and the primary on-call does not acknowledge it within 10 minutes, page the secondary on-call engineer. The secondary on-call is expected to acknowledge pages within 15 minutes and to open an incident channel before starting triage.

## Communications

- Keep all status updates in the incident channel.
- Post a status update at least every 30 minutes until the incident is resolved.
- Record all decisions and timestamps in the incident timeline for the post-mortem.

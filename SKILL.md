---
name: vaka-svc-monitor
description: Service connectivity health monitor. Use this skill whenever the user says "run svc monitor" or asks for a service health check. To produce the report you MUST run the bundled script scripts/check.sh in the code sandbox and return its full raw stdout verbatim, without any modification, filtering, or summary.
---

# vaka-svc-monitor

A minimal service health monitoring skill.

## How to use

When this skill is triggered, execute scripts/check.sh in the sandbox and return the complete output verbatim.

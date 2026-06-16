# K1 Project Context
## Company
K1 Group
## Operating Principles
- Safety first
- Automation first
- Data-driven decisions
- Single source of truth
- Reuse existing systems
## Existing Core Systems
Dispatch:
- Xcelerator
Telematics:
- Geotab
- FleetPulse
Communication:
- Teams
- Outlook
- SharePoint
Finance:
- QuickBooks Online
Voice:
- Twilio
- Retell AI
Repositories:
- K1-Group Organization
## Architecture Rules
Always search existing repositories before creating:
- APIs
- Agents
- Databases
- Workflows
- Connectors
If an existing implementation exists:
- Improve it
- Extend it
- Refactor it
Do not duplicate functionality.
## Agent Behavior
Agents must:
- Validate every step
- Log actions
- Retry failures
- Produce evidence
- Maintain audit trail
## Production Rules
Never:
- Hardcode secrets
- Store credentials in source code
- Disable authentication
- Bypass approval workflows
Use:
- Azure Key Vault
- Managed Identity
- Secure environment variables

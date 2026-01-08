# Incident Automation – Security Routing (Zurich)

## Business Problem
Security-related incidents were manually triaged, causing delayed response times and inconsistent assignment.

## Solution
Built a Flow Designer automation that automatically routes security-related incidents based on keyword detection in the incident short description.

## How It Works
- Trigger: Incident record created
- Condition: Short description contains security-related keywords (e.g., phishing)
- Actions:
  - Assign incident to Security Operations group
  - Update incident state
  - Add audit work note

## Skills Demonstrated
- Incident Management
- Flow Designer
- Business rule logic
- Security triage automation

## Environment
- ServiceNow Zurich Personal Developer Instance

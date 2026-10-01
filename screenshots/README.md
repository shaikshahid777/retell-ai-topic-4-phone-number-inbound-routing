# 📸 Topic 4 Evidence Guide

This folder is reserved for clean, traceable assessment evidence.

## Required evidence

| Evidence | What must be visible |
|---|---|
| Agent configuration | Agent name, model, voice, language, start speaker |
| Prompt | Receptionist role/objective/style |
| Test Audio | Run Test / actual web-call validation |
| Webhook | Actual call event JSON when available |
| Call History | Test call, duration, status |
| Transcript | Conversation transcript |
| Phone provisioning | Identity Verification Required screen |

## Evidence rule

Never label a `web_call` as a real inbound PSTN call. Never claim a webhook event was received unless the payload is actually visible.

Current phone provisioning is blocked by identity verification in the Retell account, so the real PSTN requirements are documented as blocked rather than fabricated.

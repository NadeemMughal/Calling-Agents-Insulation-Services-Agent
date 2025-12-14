# Insulation Services Voice Agent

## Overview
This no-code voice agent is designed for home insulation and rendering services (e.g., Vaca/Bakker Services). It handles booking, rescheduling, and canceling free surveys or calls for services like external wall insulation and render repair. Built using **Retell AI** for the voice agent and **n8n** for APIs/workflows, it integrates seamlessly with Go High Level (GHL) CRM to update contact fields and send internal notifications.

## Features
- Booking, rescheduling, and canceling appointments in GHL calendar
- Lead qualification (funding, property type, exterior type)
- Handles both new and existing customers (personalized greeting for returning callers)
- Automatic CRM field updates (address, postcode, phone, inquiry type, call summary)
- Internal email notifications to team
- Detailed confirmation and spelling verification for accuracy

## Tech Stack
- **Voice Agent**: Retell AI
- **API & Workflows**: n8n
- **CRM**: Go High Level
- **Storage (optional)**: Supabase

## Setup Instructions
1. Import the agent configuration into Retell AI.
2. Set up workflow nodes in n8n connected to Go High Level.
3. Configure credentials (API key, location ID, calendar settings).
4. Test with sample inbound/outbound calls.

## Usage
- Caller requests insulation service → Agent qualifies → Books survey → Updates GHL contact → Sends confirmation.

## Demo
Refer to the attached `project_demo.pdf` for screenshots of:
- Retell AI agent configuration
- n8n workflow nodes
- Go High Level contact and calendar updates
- Sample call flow and summary

## License
MIT

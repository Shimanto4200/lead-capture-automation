# Lead Capture Automation (Make.com)

Webhook-driven lead intake saved to Google Sheets with timestamp and status.

Built in Make.com with Webhooks and Google Sheets.

## Files

- `workflows/lead-capture-blueprint.json` — importable Make.com blueprint

## How it works

- A webhook receives a new lead
- The lead is saved to Google Sheets with a timestamp and status

## Setup

1. In Make.com, import the blueprint JSON above.
2. Replace every `YOUR_...` placeholder with your own webhook and sheet IDs.
3. Connect your own Google account — no credentials are included in this repo.

> Sanitized for public sharing: webhook and connection IDs and personal sheet references were replaced with placeholders. The scenario logic is unchanged.

More of my work: https://hafizwork.lovable.app

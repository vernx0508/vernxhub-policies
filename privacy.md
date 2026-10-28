---
title: Merkado Keys — Privacy Notice
---

# Merkado Keys — Privacy Notice

Vernxkiedooo · Updated October 28, 2026

## Operator and contact

Operated by Vernxkiedooo. Contact the server owner, vernx0508, on Discord for privacy questions or deletion requests.

## Data and purpose

The service stores your Discord user ID, a SHA-256 key hash, creation and expiration timestamps, and revoked-access status. These support key issuance, validation, expiration, and access blocks. Discord command data is processed to respond to your request.

## Key handling

Your raw key is delivered through a private Discord command response and sent to our Cloudflare service for verification. It is not stored as plain text in the key database. The PC script keeps the entered key in memory rather than saving it to disk.

## Retention

Non-revoked records become eligible for deletion seven days after expiration. Hourly cleanup removes eligible records on its next successful run. Revoked records remain to enforce access blocks until access is restored or the owner reviews a deletion request.

## Providers

Discord handles commands and responses. Cloudflare hosts the service and database. Their platform logs, backups, and retention practices are separate from cleanup of our live database.

## Your choices

Contact vernx0508 on Discord to request access to or deletion of your key record. Requests are handled manually. Deleting an active record invalidates its key. This notice covers Merkado Keys; Honeypot is a separate service with its own privacy policy at [https://honeypot.riskymh.dev/docs/privacy-policy](https://honeypot.riskymh.dev/docs/privacy-policy).

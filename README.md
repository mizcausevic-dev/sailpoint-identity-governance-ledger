# sailpoint-identity-governance-ledger

Board-readable Kinetic Gain proof repo for **SailPoint** signal coverage.

## Signal lane

- Vendor / platform: SailPoint
- Domain: Identity Governance
- Executive question: Where is this system creating exposure, waste, or decision latency?
- Proof posture: synthetic fixture, deterministic CLI, static report, and CI gate.

## Why this exists

Identity governance, certification evidence, access review gaps, and entitlement drift.

This repo is intentionally small and explicit. It gives the portfolio atlas a named, inspectable proof artifact for SailPoint without needing another hosted subdomain or exposing live customer data.

## Local run

`ash
npm install
npm test
npm run build
npm run demo
`

## Security posture

- No secrets, tokens, customer records, or live API calls.
- Fixture data is synthetic and stored in ixtures/sample.json.
- Output is deterministic and safe for public portfolio inspection.

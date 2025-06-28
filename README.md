# open-integrity-check
**Open, EU based, hardware-backed attestation for Android & later Linux phones without Google Play Services required.**

Security focused apps like banking apps are currently mostly relying on the Google Integrity API to verify that the client is running in a trusted enviroment. 

## What
* Rust verifier signs a JWT from TEE evidence.
* Android SDK & Linux CLI collect that evidence.
* Federatable, auditable, EU-hosted.

## Roadmap (high-level)
1. MVP verifier + Android SDK (Q3 2025)  
2. microG integration, root-check PoC (Q4 2025)  
3. EU-bank pilot, security audit (Q1 2026)

## Get involved
* Open an Issue · Join the Matrix room `#openintegritycheck:matrix.org`
* Draft spec: `/docs/spec.md`

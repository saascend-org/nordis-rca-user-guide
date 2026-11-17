# Nordis Technologies — Revenue Cloud sales user guide

Password-gated sales user guide for Salesforce Revenue Cloud (quote to contract to renewal).
`index.html` is an AES-256-GCM password gate (PBKDF2-SHA256, 600k iterations); the readable guide and its
screenshots exist only inside the encrypted payload.

Source: the Nordis project repo, `user-guide/` (`src/guide.template.html`, `scripts/build_guide.py`,
`scripts/gate.py`). Rebuild there, then copy `publish/index.html` here. The password is never committed.

# OpenG2P Social Registry Helm Chart

This helm contains the following components:

- Social Registry Odoo Package (Odoo + PostgreSQL)
- Mail SMTP server
- MinIO
- ODK Central
- Keymanager
- ID Generator
- OpenSearch
- Reporting (Reporting Framework + Reporting Init)
- Superset
- eSignet (eSignet + Mock Identity System)
- SR Background Tasks
- SR Landing Page

Note: Helm chart versions lower than 2.x.x were split into two parts. For versions 2.x.x and higher, there is only a single chart that installs all the required components. No need to install P2.

# OpenG2P Social Registry Helm Chart - Pack 1

Due Helm release size limitations (K8s secret, which is an etcd object,
can't exceed 1MiB), the OpenG2P Social Regsitry helm chart has been split
into two packs.

This is the first pack. This pack contains the following components:

- Social Registry Odoo Package (Odoo + PostgreSQL)
- Mail SMTP server
- MinIO
- ODK Central
- Keymanager
- ID Generator
- OpenSearch
- Reporting (Reporting Framework + Reporting Init)
- SR Background Tasks
- SR Landing Page

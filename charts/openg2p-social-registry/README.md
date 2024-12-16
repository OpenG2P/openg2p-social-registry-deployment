# OpenG2P Social Registry Helm Chart - Part 1

As the maximum size of a helm chart cannot be more than 1MiB
(each etcd object can only hold maximum of 1MiB unless configured otherwise),
the OpenG2P Social Regsitry helm chart has been split into two parts.

This is the first part. This contains the following components:

- Social Registry Odoo Package (Odoo + PostgreSQL)
- Mail SMTP server
- MinIO
- ODK Central
- Keymanager
- OpenSearch
- Reporting (Reporting Framework + Reporting Init)
- SR Background Tasks

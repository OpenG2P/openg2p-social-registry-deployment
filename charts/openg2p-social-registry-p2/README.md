# OpenG2P Social Registry Helm Chart - Pack 2

Due Helm release size limitations (K8s secret, which is an etcd object,
can't exceed 1MiB), the OpenG2P Social Regsitry helm chart has been split
into two packs.

This is the second pack. This contains the following components:

- Superset
- eSignet (eSignet + Mock Identity System)

Skip this pack if you dont want to install these components.

## IMPORTANT

Whatever installation name chosen of Pack 1, the same will have to be given for pack 2 with suffix "-p2".

For example, if you want the installation name to be "sr", then the name for pack 1 will have to be "sr", and the name for pack 2 will have to be "sr-p2".

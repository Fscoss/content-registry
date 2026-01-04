# content-registry
This repository provides a minimal, system-internal content blocking registry designed for DNS resolvers, browsers, and other network components.

The registry is distributed as plain text.
Each entry is written on a single line, and columns are separated by a vertical bar ("|").

The first column contains a domain name or an IP address.
The second column contains an attribute ID.
The third column contains the last updated date.

Format:
domain_or_ip|attribute_id|last_updated

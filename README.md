# MariaDB CBOM GCM plugin 0.0.21

This branch contains the prepared plugin ZIP and its SHA-256 checksum.

The changes preserve algorithm classification fixes and resolve configured TLS cipher policies on the target host, normalize recognized cipher suites to IANA names, and populate protocol cipher lists. Original expressions are retained in the CBOM for audit.

Validation: 31 local regression cases, collector self-test, and fresh ZIP extraction self-test passed. Live MariaDB discovery and ingestion on GCM v2.0.3.0 have not been tested. A fresh discovery is required; the historical CBOM does not contain resolved suites.

Download mariadb-cbom-gcm-0.0.21.zip from this branch, or clone the branch and copy the ZIP.

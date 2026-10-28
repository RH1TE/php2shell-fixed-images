# RHITE PHP2Shell fixed images

Reproducible emergency derivatives used to remove vulnerable PHP runtimes from RHITE application images affected by CVE-2026-109618 and CVE-2026-109619.

Each image preserves the exact pinned application base and replaces only the PHP CLI, PHP-FPM binary and matching OPcache extension with PHP 8.3.36 from the corresponding official PHP Alpine branch.

These images are operational security artifacts, not upstream releases. Deployment remains pinned by digest after CI publication.

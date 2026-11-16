# qa-cvss-un-001-pub

IVAS QA seed (BT26-783). Library matching row must contain both:

- CVSS unknown (U): org.threeten:threetenbp 1.6.8 -> CVE-2024-23082 (NVD Deferred, no CVSS)
- CVSS 0.0 (N): symfony/process v3.4.47 -> CVE-2024-51736 (CVSS 3.1 base 0.0)

Do not change dependency versions.

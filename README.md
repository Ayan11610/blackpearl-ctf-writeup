# Black Pearl

## Recon
- Enumerated DNS and discovered the `blackpearl.tcm` virtual host.
- Found Navigate CMS under `/navigate`.

## Exploitation
- Exploited Navigate CMS 2.8 RCE.
- Enumerated SUID binaries.
- Abused SUID PHP for privilege escalation.

## Result
- **Access:** Root

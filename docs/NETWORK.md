# Networking quickstart

Starter notes for network tooling projects:

- Inspect: `ip addr`, `ip route`, `ss -tulpn`.
- Debug DNS: `dig +trace`, `drill`.
- Trace paths: `mtr`, `traceroute`.
- Capture: `tcpdump -i any -w capture.pcap`, read with Wireshark.
- Firewall (nftables): `nft list ruleset`; keep rules in git.
- See also: dns-template, tor-template.

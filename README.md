# VPN Setup and Privacy Protection Report
# Objective
To understand the role of Virtual Private Networks (VPNs) in protecting user privacy, securing communication, and masking IP addresses by setting up and testing a free VPN client.
# Tools Used
ProtonVPN (Free Tier) – Reputable VPN provider offering secure connections.
Browser (Firefox/Chrome) – For verification of IP and browsing tests.
whatismyipaddress.com – To confirm IP changes.
# Setup Steps (Methodology)
1.Choose VPN Provider
Selected ProtonVPN for its strong reputation, no-logs policy, and AES-256 encryption.
2.Download & Install Client
Downloaded ProtonVPN Free client from official website.
Installed on Linux/Windows.
3.Connect to VPN Server
Logged in with credentials.
Chose the nearest free server (Netherlands) to reduce latency.
Connection status showed: Connected (screenshot placeholder here).
4.Verify IP Change
Before VPN: IP detected as ISP-assigned local address.
After VPN: IP detected as Netherlands-based IP.
5.Traffic Encryption Test
Browsed websites and confirmed HTTPS traffic was encrypted.
Ran ping tests; routing confirmed via VPN tunnel.
6.Performance Comparison
Browsing speed with VPN slightly slower (latency increase ~40–60 ms).
Without VPN, speeds returned to normal.
# Research: VPN Encryption & Privacy Features
Encryption:
ProtonVPN uses AES-256 encryption with strong key exchange (RSA-4096 / Diffie-Hellman).
Protocols:
OpenVPN and IKEv2/IPsec supported for secure tunneling.
Privacy Protections:
Masks IP address from websites and ISPs.
Prevents traffic sniffing on public Wi-Fi.
No-logs policy ensures user activity isn’t stored.
# Benefits & Limitations
✅ Benefits:
Protects against snooping on insecure networks.
Masks IP and location for anonymity.
Prevents ISP tracking and censorship.
Useful for securing remote work.
⚠️ Limitations:
Free VPN servers may have speed limitations.
VPN doesn’t protect against phishing/malware (separate tools needed).
Trust depends on the provider’s no-logs policy.

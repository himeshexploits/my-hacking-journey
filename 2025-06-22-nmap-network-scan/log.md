# Nmap Network Scan - Day 1
**Date:** 2025-06-22

## What I Did
- Used `netdiscover` to list all devices on my network.
- Noticed an unknown IP (like 192.168.0.116) and got suspicious.
- Ran `nmap -A 192.168.0.116` to scan the target.

## What Happened
- I thought it was a rogue device or hacker.
- Turned out... it was my own Windows machine (LOL)
- Realized I had multiple interfaces and my firewall was behaving weird.

## What I Learned
- Always check what devices are *actually yours* before panicking.
- `nmap -A` gives detailed info: OS, ports, services, even versions.
- `netdiscover` is great for quick LAN scans, but double-check MACs/IPs.

## Why This Was Cool
This was my first real "WTF moment" in hacking. Even though I messed up, it taught me more than getting it right the first time.

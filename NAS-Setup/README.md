# Home NAS Setup — Centralized Storage Solution

## Summary
I built a DIY NAS using an old MSI laptop and open‑source tools to create a personal cloud for storing and remotely accessing important files. The project strengthened my confidence in configuring systems, troubleshooting hardware limitations, and setting up secure cross‑platform access through VPN and mobile file‑management tools.

## What I Built
I set up a TrueNAS‑based storage system using a dedicated SATA SSD as the boot drive, which resolved the performance issues I encountered when attempting to boot from USB flash media. The system stores files on a WD 1TB external drive, organized into datasets and shared over SMB for easy access across devices.

To support secure remote connectivity, I configured Tailscale as a VPN solution and enabled SSH within TrueNAS. I also integrated FE File Explorer on iOS, allowing seamless access to the NAS from my iPhone. The final setup provides reliable, cross‑platform storage and remote access using mostly hardware I already had available.

## Key Troubleshooting
- Resolved SMB share access issues by adjusting firewall and folder permissions
- Diagnosed network visibility problems using ping and IP scanning tools

## Skills Demonstrated
- Troubleshooting
- Documentation
- Networking basics
- Permissions and access control

## Full Write-Up
[Link to Google Doc]


I # Home NAS Setup — Centralized Storage Solution

## Summary
I built a DIY NAS using an old MSI laptop and open‑source tools to create a personal cloud for storing and remotely accessing important files. The project strengthened my confidence in configuring systems, troubleshooting hardware limitations, and setting up secure cross‑platform access through VPN and mobile file‑management tools.

## What I Built
I set up a TrueNAS‑based storage system using a dedicated SATA SSD as the boot drive, which resolved the performance issues I encountered when attempting to boot from USB flash media. The system stores files on a WD 1TB external drive, organized into datasets and shared over SMB for easy access across devices.

To support secure remote connectivity, I configured Tailscale as a VPN solution and enabled SSH within TrueNAS. I also integrated FE File Explorer on iOS, allowing seamless access to the NAS from my iPhone. The final setup provides reliable, cross‑platform storage and remote access using mostly hardware I already had available.

## Key Troubleshooting
The biggest issue I encountered during this project was attempting to use a USB flash drive as the boot device for TrueNAS. I initially tried configuring two separate flash drives—one for installation media and one intended to serve as the system’s boot drive—but the hardware simply wasn’t suited for the task. Boot attempts were extremely slow, often taking over two hours, and repeated formatting attempts failed to produce a stable or supported boot environment.

After researching the issue, I replaced the USB boot device with an external SATA SSD. Once formatted and connected, the system booted cleanly within minutes, confirming that the SSD was the correct solution. This change resolved the performance bottleneck entirely and allowed the rest of the setup process to move forward smoothly.

## Skills Demonstrated
This project strengthened several core IT support skills. I demonstrated the ability to troubleshoot hardware and software issues, especially when diagnosing the limitations of USB flash drives as a boot device and identifying the SATA SSD as the correct solution. I configured key TrueNAS services, including storage pools, datasets, SMB sharing, SSH access, and secure remote connectivity through Tailscale.

Throughout the process, I relied on researching documentation, community forums, and AI tools to compare solutions, validate assumptions, and troubleshoot effectively. I tested different configurations, evaluated system behavior, and confirmed fixes through measurable results. I also applied a user‑focused mindset by ensuring the system could be reverted back to Windows if needed, preserving flexibility and protecting the original environment. The final setup showcases cross‑platform compatibility, secure remote access, and practical, resourceful problem‑solving from start to finish.

## Full Write-Up
A detailed, step‑by‑step walkthrough of this project — including hardware notes, installation steps, troubleshooting logs, configuration screenshots, and lessons learned — is available in my full project write‑up: [Link to Google Doc]


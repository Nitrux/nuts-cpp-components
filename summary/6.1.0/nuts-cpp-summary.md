Nitrux 6.1.0 introduces major performance upgrades, structural refinements, and critical security updates to enhance your desktop experience.

**Desktop Environment and User Interface**

*   **MauiKit 4.0.3:** Updated the foundational MauiKit framework and core Maui Apps, including Buho, Clip, Nota, Index, VVave, Shelf, Pix, and Fiery, bringing interface refinements, stability fixes, and layout optimizations.

*   **Hyprland Updates:** Upgraded to Hyprland 0.55.1, featuring a newly rewritten configuration utilizing Lua for improved flexibility.

*   **Application Launcher:** Replaced Wofi with Vicinae, a Raycast-inspired launcher designed for faster application switching and enhanced keyboard navigation.

*   **System Audio and Status:** Adjusted PipeWire latency parameters to improve overall audio performance and refined Waybar styling for better desktop information layout.

**System Architecture and Performance**

*   **Linux Kernel 7.0.8:** Features the latest Linux kernel 7.0.8 carrying CachyOS performance patches for optimized hardware responsiveness.

*   **Memory Management:** Introduced dmemcg-booster, an OpenRC-compatible implementation of Valve's memory management daemon, to improve system resource allocation under heavy workloads.

*   **Hardware Compatibility:** Added an HID-BPF loader triggered via udev events to expand support for input devices, alongside the inclusion of Fatresize and the KDE Partition Manager.

**Security and Infrastructure**

*   **Vulnerability Mitigations:** Resolves key security vulnerabilities, including mitigations for Copy Fail (CVE-2026-31431), Dirty Frag (CVE-2026-43284), Fragnesia (CVE-2026-43500), and ssh-keysign-pwn (CVE-2026-46333).
    
*   **Disk and Access Security:** Added native YubiKey two-factor authentication support for LUKS-encrypted disks and PAM integration for Universal 2nd Factor (U2F).

[Learn more...](https://nxos.org/changelog/release-announcement-nitrux-6-1-0/)

Nitrux 7.0.0 introduces a compartmentalized architectural overhaul, critical component updates, and interface refinements to enhance your desktop experience.

**Desktop Environment and User Interface**

*   **MauiKit 4.0.4:** Updated the foundational MauiKit framework, MauiKit Frameworks, and core Maui Apps, including Pix, Nota, Buho, Clip, Fiery, Shelf, VVave, Index, and Station, to provide a unified design language and expanded Wayland support.
    
*   **Workspace Environment:** Transitioned to a specialized architecture where shell components run as an independent, rootless user-session hierarchy governed by nwsm, an OpenRC-based session lifecycle manager.
    
*   **Core Shell Components:** Introduced Valenz, Marina, Desklock, QMLogout, Workspace Settings, and NudgeOSD as deliberate, specialized components for workspace navigation, session locking, configuration, and notifications.
    
*   **Hyprland Updates:** Upgraded to Hyprland 0.55.4, alongside updates to all included Hypr utilities for improved window management.

**System Architecture and Performance**

*   **Linux Kernel 7.2.6:** Features the latest Linux kernel 7.2.6 carrying CachyOS performance patches for optimized hardware responsiveness.
    
*   **Software Management:** Adopts a boundary-driven approach utilizing AppBox and Flatpak for user-space applications, visually guided by the newly introduced AppFinder GUI.
    
*   **Graphics Compatibility:** Upgraded the NVIDIA Open Kernel Module to version 615.71.09 to improve display performance, and added the C++ based Hyprscreend daemon to manage monitor modes and scaling.

**Security and Infrastructure**

*   **Vulnerability Mitigations and Hardening:** Expanded kernel and network security tuning with restricted kernel pointers, restricted eBPF, RFC 1337 protection, and a fix for the ssh-keysign-pwn mitigation affecting Proton.
    
*   **Disk Encryption:** Switched Calamares encrypted partition creation from LUKS1 to LUKS2, utilizing Argon2id for key derivation during boot keyfile creation.
    
*   **Networking and Firewalls:** Upgraded Cinderward to version 0.0.6 to group advanced firewall behavior options, and updated Wirecloak to version 0.0.4 with a dedicated Tunnel Control section.
    
*   **Nitrux Update Tool System:** Updated to version 3.0.3, featuring a redesigned interface utilizing responsive MauiKit-style cards to display system status and operation progress.

[Learn more...](https://nxos.org/changelog/release-announcement-nitrux-7-0-0/)

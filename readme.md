# SD Card Contents 
This setup supports Stock Sysnand, Atmosphere Emunand, and Android. It includes a variety of homebrew applications and tools. The setup is based on the V6S modchip and is built on Horizon OS 18.1.0.

## Versions
- Hekate: 6.2.2
- Nyx: 1.6.4
- Atmosphere: 1.8.0-prerelease
- V6S Firmware: 1.3

## Installed
| Name | Version | Description |
| ---- | ------- | ----------- |
| Horizon OS (Emunand) | 18.1.0 | Switch OS |
| Hekate | 6.2.2 | Bootloader |
| Nyx | 1.6.4 | Bootloader UI |
| Atmosphere | 1.8.0-prerelease | CFW |
| Emunand hosts block | N/A | Blocks Nintendo servers on Emunand |
| V6S Firmware | 1.3 | Firmware for V6S modchip |
| DBI | 658 | Title Installer |
| JKSV | 08.06.2024 | Save Manager |
| FTPD | v3.1.0 | FTP Server |
| Breeze | beta 95e | Cheat code manager |
| AIO Switch Updater | 2.23.2 | Homebrew Updater |
| Emuiibo | 1.1.1 | Amiibo Emulator |
| Emuiibo - Overlay | 1.1.1 | Amiibo Tesla Overlay |
| Amiigo | 2.3.2 | Amiibo Manager |
| SimpleModManager | v2.1.2 | LayeredFS Mod Manager |
| SysClk | 2.0.1 | Overclocking |
| SysClk - Overlay | 2.0.1 | Overclocking Tesla Overlay |
| NXThemesInstaller | 2.7.1 | Theme Installer |
| sys-patch | firm 19.0.0 | Sigpatches |
| sys-patch - Overlay | firm 19.0.0 | Sigpatches Tesla Overlay |
| MissionControl | 0.12.0 | 3rd Party Controller Support |
| nx-ovlloader | 16.0.0 | Overlay Loader |
| ovlmenu | 1.2.3 | Overlay Menu |
| chiaki | 2.2.0 | PS4 & PS5 Remote Play |
| retroarch | 1.17.0 | Emulator (requires placing retoarch folder in sd root) |

## NSPs
| Name | Version |
| ---- | ------- |
| retroarch | N/A |

# Setup
1. Copy `atmosphere`, `bootloader`, `config`, `payload.bin` to the root of your SD card.
2. Boot into Hekate and create a SD partition Emunand and Android partition if desired.
    - Optional: Restore emunand partition from backup.
3. Copy all files and folders to root of SD card, replacing any files.
4. If sigpatches are needed, use `sys-patch`.

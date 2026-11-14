# 7KR Optimizer — Windows beta

[Download the beta installer](https://github.com/Winzartt/7KR_Optimizer_Releases/releases/tag/v0.1.9-beta.1)

New heroes and costumes, including Eve and Judas, with their dedicated weapon images and reference data.

The launcher starts without a console or automatic browser window. Click Open Optimizer to open the interface.

Existing users: Check, Download, then Install in the launcher. Inventories, settings and saved builds are preserved. Dedicated weapons appear on the hero sheet when equipped and synchronized.

Validation: packaged resources checked, isolated upgrade preserves fictional user data, and executable self-test passes. The owner confirmed the new dedicated weapons display locally. Combat effects are not newly calculated. Known issues remain: slow searches with some min/max filters and a one-point defense preview discrepancy.

Download the installer EXE below, not the source archives. Wireshark and Npcap are required separately. The installer is unsigned.


This repository distributes the application only. The development repository remains private.
Install Wireshark with Npcap from https://www.wireshark.org/download.html before starting synchronization.
Launch the game yourself after starting synchronization. No account password is required by this app.
User data is stored in `%LOCALAPPDATA%/7KR_Optimizer` and is preserved by updates.
The launcher checks this repository for updates over HTTPS; downloading and installation require your action.
No inventory is uploaded. GitHub receives ordinary connection information when updates are checked or downloaded.
Updates download a complete installer; they are not differential patches. SHA-256 verifies download integrity, not an independent signature.

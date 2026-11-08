# Notices

This repository carries Tonegakko's firmware and installer as built files. What they are built from, and under which
licences:

| Part | Licence | Source |
| --- | --- | --- |
| fm1-base, the platform the firmware, the installer page and the follow page are built on (unmodified, at commit `b0976f295ccaeaf77a8053a5a785a9cc21f5345f`) | MPL-2.0 (`LICENSES/MPL-2.0.txt`) | <https://github.com/charlesvestal/fm1-base/tree/b0976f295ccaeaf77a8053a5a785a9cc21f5345f> |
| felucca-bsp, fm1-base's board support (a submodule of it, at commit `5b0879bfadc69a17dbebb917fb6b86d516f19c44`) | MPL-2.0 | <https://github.com/hugelton/felucca-bsp> |
| The SBC encoder of Android's Bluetooth stack, JieLi AC79 SDK parts and the radio tables in fm1-base | Apache-2.0 (`LICENSES/Apache-2.0.txt`) | in fm1-base, as above |
| micro-ecc (Kenneth MacKay) | BSD-2-Clause (`LICENSES/BSD-2-Clause-micro-ecc.txt`) | in fm1-base, as above |
| m-bootloader 1.2 (Julius Vitkauskas), which the installer offers | MIT (`LICENSES/MIT-m-bootloader.txt`) | <https://github.com/jvitkauskas/m-bootloader> |
| Barlow Semi Condensed (The Barlow Project Authors), drawn into the firmware's fonts | SIL OFL 1.1 (`LICENSES/OFL-1.1-Barlow.txt`) | <https://github.com/jpt/barlow> |

fm1-base's own licensing notes (what is MPL-2.0 and where each part comes from) are in its `LICENSING.md`.
Tonegakko's own code (the game: the island, the Sonari, their music and pictures) is not published here.

M-VAVE and FM-1 are trademarks of their owners. Tonegakko is not made, endorsed or supported by M-VAVE.

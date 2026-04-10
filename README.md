# canoe_tools

Tools and resources for the OnePlus 15 Chinese variant (Canoe/PLK110).

## Contents

- **ota/** — Scripts to fetch OTA download links from [roms.danielspringer.at](https://roms.danielspringer.at), plus an Android 17 Beta 2 flashing guide with direct links
- **EfsTools/** — CLI tool to read/write Qualcomm modem EFS over USB (alternative to QPST EFS Explorer) (submodule)
- **qpst-enable-all-lte-bands-plk110/** — Modded policyman configs to unlock all hardware-supported LTE/5G bands (submodule)
- **gbl_root_canoe/** — EDK2-based GBL/UEFI secure boot exploit for rooting Qualcomm devices (submodule)

## Clone

```sh
git clone --recurse-submodules git@github.com:PeronGH/canoe_tools.git
```

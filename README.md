# MUI virtual node-list tester firmware

This repository publishes test firmware artifacts for the Meshtastic MUI virtual node-list candidate.

These builds are for tester flashing only. They are not Meshtastic stable release artifacts.

Current candidate source:

- Firmware: `RCGV1/firmware-Fork`, branch `candidate/mui-node-list-tester-20260825`, commit `6da76d5b60534328928267861273bf6d0b92579e`
- Device UI: `RCGV1/device-ui`, branch `candidate/virtual-node-list-improvement-20260824`, commit `9e84d74cb9bc4f2ef4cc577912b3d11b2ad29504`
- Targets: `elecrow-adv-24-28-tft`, `elecrow-adv-35-tft`, `elecrow-adv1-43-50-70-tft`, `heltec-v4-tft`, `picomputer-s3-tft`, `rak_wismesh_tap_v2-tft`, `seeed-sensecap-indicator-tft`, `t-deck-tft`, `unphone-tft`
- Required compile definition: `DEVICE_UI_MUI_VIRTUAL_NODE_LIST`

The `Build candidate firmware` workflow produces release assets and a manifest that the dedicated tester web flasher can consume.

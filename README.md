# MUI virtual node-list tester firmware

This repository publishes test firmware artifacts for the Meshtastic MUI virtual node-list candidate.

These builds are for tester flashing only. They are not Meshtastic stable release artifacts.

Current candidate source:

- Firmware: `RCGV1/firmware-Fork`, branch `candidate/mui-node-list-tester-20260824`, commit `599f1c36ec5738cae8d330b095ff9f3f868b1ea3`
- Device UI: `RCGV1/device-ui`, branch `candidate/virtual-node-list-improvement-20260824`, commit `9e84d74cb9bc4f2ef4cc577912b3d11b2ad29504`
- Target: `t-deck-tft`
- Required compile definition: `DEVICE_UI_MUI_VIRTUAL_NODE_LIST`

The `Build candidate firmware` workflow produces release assets and a manifest that the dedicated tester web flasher can consume.

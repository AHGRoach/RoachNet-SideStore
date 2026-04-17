# RoachNet SideStore Source

This repo publishes the SideStore / AltSource feed for `RoachNetiOS`.

Primary source URL:

`https://raw.githubusercontent.com/AHGRoach/RoachNet-SideStore/main/apps.json`

What it carries:

- `RoachNetiOS` release metadata
- direct IPA install URL
- app permissions for QR pairing and local companion networking
- screenshots and icon assets for SideStore

Website links should point users to:

- source URL: `https://raw.githubusercontent.com/AHGRoach/RoachNet-SideStore/main/apps.json`
- direct IPA: `https://github.com/AHGRoach/RoachNet-iOS/releases/latest/download/RoachNetiOS-v0.1.3-unsigned.ipa`

The source exists so the iOS install lane feels like the rest of RoachNet: one clear path, no mystery files, no guessing which IPA is current. On-device, the IPA should be downloaded and shared into SideStore instead of depending on undocumented deep links.

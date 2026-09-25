# Kydora Home downloads

Download the latest [Windows installer and Android APK](https://github.com/kayden-pixel/Kydora-Home-Downloads/releases/latest). Kydora Home checks this public release feed for updates without requiring a GitHub token. The application source remains in a private repository.

## Install

1. Install the Windows setup executable and Android APK from the same release. The Windows installer is unsigned, so Windows may show a publisher warning.
2. Install and connect Tailscale on the phone and each Windows PC for access between different locations. Set **Relay address** to `tailscale` in the Windows app. Keep the PC powered on, signed in, and connected.
3. Pair each device once with a QR or pasted invite. On the same Wi-Fi, the Android app can also discover nearby PCs. Pairing requires approval on the PC.
4. Use **Home** on the owner phone to choose trusted members. Each PC approves its first Home invitation, then can send files to the group.

Downloads are verified with the SHA-256 digest shown on each GitHub release asset. The Android APK is currently signed with the same development key as previous Kydora Home APKs. Keep that key for future updates. Transfers use device identities and end-to-end encryption; Tailscale provides network reachability.

Copyright © 2026 kayden-pixel. All rights reserved.

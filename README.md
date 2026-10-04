# YASK RT5370 USB Wi-Fi Kernel Builder

GitHub Actions builder for a YASK Android 5.15 kernel with:
- Ralink/MediaTek RT5370 (148f:5370) support
- RT2800USB + RT53XX support
- embedded `rt2870.bin` firmware
- additional common USB Wi-Fi drivers
- flashable AnyKernel3 output

## Build
1. Upload this repository's files to GitHub.
2. Open **Actions**.
3. Select **Build YASK CLO + USB Wi-Fi + embedded RT firmware**.
4. Tap **Run workflow**.
5. Wait for the build to finish.
6. Download artifact **YASK-USB-WIFI-CLO-KSU**.
7. Flash the generated ZIP from TWRP.

**Do not flash this builder ZIP itself.**

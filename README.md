# WebPSP

Web portal for a browser-based PSP emulator. The playable emulator is provided by the community PPSSPP WebAssembly project at https://root-hunter.github.io/ppsspp-web/ and is embedded here. If browser embedding is blocked, use the "新窗口打开" link.

## Deploy
A GitHub Actions workflow publishes this repository to GitHub Pages on every push to main. In repository Settings → Pages, choose **GitHub Actions** as the build and deployment source if it is not already selected.

After the first successful workflow, the site URL is:
https://henry6666666.github.io/Psp-simulater/

## Emulator
The upstream browser build supports local PSP game imports and runs the PPSSPP WebAssembly core. Game files are not included or uploaded by this portal. Performance and compatibility depend on the browser and device.

Upstream source and build notes: https://github.com/root-hunter/ppsspp-web
Original emulator: https://github.com/hrydgard/ppsspp

PPSSPP is GPL-2.0-or-later. This repository is an independent portal and is not affiliated with Sony or PPSSPP.

# LanCast 2.0.0

Play videos and music, web videos and whole screens on any screen in your home, over your own Wi-Fi or a cable. No internet needed (except to open web pages), no account.

## Downloads

- **Windows 10 (1903+) and 11, 64-bit:** `LanCast-Windows-2.0.0.zip` from the **[latest release](https://github.com/kabi047/lancast/releases/latest)**. Unzip and run `LanCast.exe`; no installer.
- **Android phones, tablets and TVs:** **[LanCast on Google Play](https://play.google.com/store/apps/details?id=app.lancast)** (open to testers now, everyone after launch). Buying Pro and updates work through Google Play.

## Windows

Run `LanCast.exe`. The first start unpacks it (a few seconds). If Windows asks about the firewall, allow **private networks** only.

- **This PC as a screen:** it opens full screen and waits. Choose it on your phone.
- **Show this PC on another screen:** press **S**. Choose the TV, phone, tablet or PC (LanCast open on it), then **Show this screen**. Sound goes too.
- **Control this PC from a phone:** leave "Let a phone or tablet showing it control this PC by touch" on. On the phone: tap to click, drag to drag, hold for right-click, two fingers to scroll, ⌨ to type.
- **Second display (extend instead of mirror):** install a virtual display driver (for example the open-source *Virtual Display Driver* project), arrange the new display in Windows Settings > System > Display, then choose it under *Which display*.
- **Without the window:** `LanCast.exe --send 192.168.1.20 [display number]`. Add `--no-control` to refuse control. `--windowed` starts the screen in a window.

Quality: up to 4K and 60 fps when the receiving screen has LanCast Pro, otherwise 1080p and 30 fps. LanCast uses your graphics card's encoder (NVIDIA, AMD, Intel), or Windows' own.

## Android

- **Your files:** choose a screen, tap a video.
- **Web videos:** tap the globe on the home screen. Every video and song on a page gets a cast button in its corner. Or in any app tap **Share → LanCast**. Videos protected by their service (Netflix, Prime Video, Hotstar and similar) can't be sent.
- **Mirror your phone:** Settings → **Mirror this screen** (Android 10+ for sound).
- **Other TVs and speakers:** TVs that support "Play To" (DLNA) appear under *Other TVs and speakers*.
- **Wired:** connect the screen by Ethernet or USB tethering and enter the address it shows.

## Free and Pro

Free: up to 1080p and 30 fps, 90 minutes at a time. Pro (one payment on Google Play): up to 4K/60 fps, HDR, no time limit, subtitles, equalizer, live stats, mirroring and web videos at full quality.

## Licences

LanCast is © Vibe Coded. It uses open-source software, listed in the app (Settings → Licences and credits) and in `THIRD-PARTY-NOTICES.txt` inside the Windows download. The Windows app runs FFmpeg (GPL v3) as a separate program; its source is at https://ffmpeg.org.

Terms and privacy: https://sites.google.com/view/lancast-privacy-policy

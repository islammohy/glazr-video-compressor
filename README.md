# Glazr Video Compressor

Free video compressor for **Windows 10/11** and **macOS** by [IGY Apps](https://igy-apps.com).
Drop videos, pick where they will be sent (WhatsApp, Email, Discord, Telegram,
Instagram/TikTok, YouTube, or "under N MB"), press Compress.

- Works **offline**. Your videos never leave your computer, and the originals are never changed.
- No watermark, no length limit, no paid edition.
- Arabic, English, French and German.

![Glazr Video Compressor](docs/en-light-done.png)

## Download

Get the newest version from **[Releases](https://github.com/islammohy/glazr-video-compressor/releases/latest)**:

| System | File |
|---|---|
| Windows 10/11 (64-bit) | `Glazr-Video-Compressor-<version>-Windows-x64-Setup.exe` (or the portable `.zip`) |
| macOS, Apple Silicon (M1 and later) | `Glazr-Video-Compressor-<version>-macOS-arm64.dmg` |
| macOS, Intel | `Glazr-Video-Compressor-<version>-macOS-x64.dmg` |

Check a download against `SHA256SUMS.txt` in the same release if you like:
`certutil -hashfile <file> SHA256` on Windows, `shasum -a 256 <file>` on macOS.

Windows may show "Windows protected your PC" for a new release. Choose **More info › Run anyway**.

This repository holds downloads only. The application's source code is not public.

## Privacy

Compression happens on your computer. When online, the app downloads one banner and the
newest version number from igy-apps.com, sending only the app name, the system, the
language and where it was installed from. Offline, the banner is a link to the website.

## Open-source parts

The app includes FFmpeg (GPLv3), Qt/PySide6 (LGPLv3) and the IBM Plex Sans Arabic font
(OFL). Their licenses are in the app's `licenses` folder, and each release includes the
FFmpeg source code it was built from.

## Problems and ideas

Open an [issue](https://github.com/islammohy/glazr-video-compressor/issues). Please don't
attach private videos.

---

# Glazr Video Compressor بالعربية

برنامج مجاني لضغط الفيديو على **ويندوز 10/11** و**ماك** من [IGY Apps](https://igy-apps.com).
اسحب الفيديوهات، واختر أين سترسلها (واتساب، البريد، ديسكورد، تيليجرام، إنستجرام/تيك توك،
يوتيوب، أو «أقل من N ميجابايت»)، ثم اضغط «ضغط».

- يعمل **بدون إنترنت**، والفيديوهات لا تغادر جهازك، والأصل لا يتغيّر أبدًا.
- بلا علامة مائية، وبلا حد لطول الفيديو، وبلا نسخة مدفوعة.

**التنزيل:** من صفحة [الإصدارات](https://github.com/islammohy/glazr-video-compressor/releases/latest).
لويندوز ملف `Setup.exe`، ولماك ملف `.dmg` (‏arm64 لأجهزة M1 وما بعدها، وx64 لأجهزة Intel).
إذا ظهرت رسالة «Windows protected your PC» اضغط **More info** ثم **Run anyway**.

![Glazr Video Compressor بالعربية](docs/ar-dark-running.png)

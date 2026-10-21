# TVA Timeline

A retro TVA-inspired Garmin watch face with an animated timeline, Miss Minutes, and Main and Night modes.

**Version 1.0.3 — Early Access**

## Download

**[Download the v1.0.3 PRG installation package](https://github.com/ramadhian-e/tva-timeline/releases/download/v1.0.3/TVA-1.0.3-SEMUA-MODEL-PRG.zip)**

[View the release notes and downloads](https://github.com/ramadhian-e/tva-timeline/releases/tag/v1.0.3)

On the release page, choose **TVA-1.0.3-SEMUA-MODEL-PRG.zip** under **Assets**. The automatically generated **Source code** archives contain the repository files; use the PRG package to install the watch face.

## Features

- **Main:** a curved branching timeline with orange safety boundaries and a moving white pulse. Miss Minutes peeks from the four o'clock edge, jumps to the center, points, displays a final message, and returns.
- **Night:** the preserved dark amber design with walking Miss Minutes, a decorative loading bar, and a process status table.
- Automatic Main/Night switching, with Night scheduled from **21:00 to 06:00** by default, plus manual mode settings where available.
- Time, date, battery, heart rate, daily calories, steps, altitude, and watch-sensor temperature when available.
- Round and rectangular layouts for the supported Garmin models.

Wake animations run for up to 10 seconds, then become static. The Night loading sequence is decorative. Sensor temperature can be affected by body heat.

## Supported devices

The package contains **204 PRG files covering 123 Garmin SDK model IDs**, including supported regional variants. Examples include the Forerunner 165 / 165 Music and 965, supported fenix 6X and fenix 8 variants, and Venu Sq / Sq Music, Sq 2 / Sq 2 Music, and X1.

Check **DAFTAR-MODEL-DAN-FILE.txt** or **DAFTAR-MODEL-DAN-FILE.csv** inside the download for your exact model and PartNumber. Device families can have separate folders for size, Music editions, and other variants.

## Install using USB

1. Download the PRG ZIP above and **extract it on your computer**.
2. Open **PRG → your exact model → matching PartNumber** and copy **TVA103.prg**. Windows may display the filename as **TVA103**, with the type **PRG File**.
3. Connect the watch using a USB data cable. In File Explorer, open the watch's storage and navigate to **GARMIN → APPS**.
4. Paste **one TVA103.prg directly into APPS**, alongside the other PRG files. Leave the existing files in place.
5. Wait until the transfer finishes. Eject if the option is available; for an MTP device without Eject, close the watch's file window after the transfer completes and unplug USB.
6. On the watch, open **Watch Face**, select **TVA Timeline**, and apply it. Menus and buttons vary by model.

### Windows example: fenix 6X Pro ASIA Solar

The storage path shown on the user's Windows device is:

```text
This PC → fenix 6X Pro ASIA Solar → Primary → GARMIN → APPS
```

Other models may use **Internal Storage**, or show **GARMIN** directly on a removable drive. Follow the storage name actually shown by your device.

For the **three fenix6xpro folders in this v1.0.3 package only**, the files in **006-B3291-00**, **006-B3516-00**, and **006-B3783-00** have identical SHA-256 hashes. You may use one copy, such as **PRG/fenix6xpro/006-B3291-00/TVA103.prg**. This does not establish which PartNumber your watch has, and does not automatically apply to other models or packages.

For other model variants, check **GARMIN/GarminDevice.xml → Model → PartNumber**. The file may appear as **GarminDevice** with a browser icon when extensions are hidden. Copy it to your computer and open it as text to read the PartNumber.

Detailed Indonesian instructions are included in the package:

- **TUTORIAL-INSTALL-PRG.txt:** all supported models and troubleshooting.
- **TUTORIAL-FENIX-6X-WINDOWS.txt:** the Windows example above.
- **PRG/your-model/BACA-DULU.txt:** guidance for models with multiple PartNumbers.

## Feedback

This is an early access release. Simulator testing does not replace physical-device testing on every supported model. Animation performance and available sensor data vary by watch and firmware.

Please [open an issue](https://github.com/ramadhian-e/tva-timeline/issues) with your watch model, firmware version, app version, and the steps that reproduce the problem. Include a photo or video if it helps explain the issue.

Unofficial fan project. Not affiliated with or endorsed by Marvel, Disney, or Garmin.

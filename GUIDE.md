# LivePointer user guide

Written in Simplified Technical English (ASD-STE100): short sentences, one instruction per sentence, the same word for the same thing.

## 1. Description

LivePointer is a pointer and a slide remote for presentations. It has two parts:

- LivePointer for Mac. A free menu-bar app. It draws the pointer on the Mac's display and sends the slide keys to PowerPoint or Keynote.
- LivePointer for iPhone. The controller. It shows a live preview of the Mac's display. You touch the preview to point.

The two parts talk to each other over your local network. They do not use a server. They do not collect data.

## 2. Requirements

- A Mac with macOS 15 or later.
- An iPhone with iOS 17 or later.
- The Mac and the iPhone on the same Wi-Fi network, or the Mac on the iPhone's Personal Hotspot.
- PowerPoint or Keynote on the Mac, for the slide controls.

## 3. Install the Mac app

1. Download LivePointer-1.1.pkg from https://github.com/JH-Eric-Yang/LivePointer/releases/latest.
2. Open the file. Click Install.
3. LivePointer starts in the menu bar. It has a cursor icon. It has no Dock icon.
4. When macOS asks for Local Network access, click Allow.

The app and the installer are notarized by Apple. macOS opens them without a warning.

## 4. Give the Mac app its permissions

The Mac app asks for three permissions. Each one enables one function. Give only the ones you need.

| Permission | Function | How to enable |
|---|---|---|
| Screen Recording | The live preview on the iPhone | Menu bar icon > Enable Screen Preview (Screen Recording)… |
| Accessibility | The slide keys (Prev, Next, Start show) | Menu bar icon > Enable Slide Keys (Accessibility)… |
| Full Disk Access | The slide thumbnails on the iPhone | Menu bar icon > Enable Slide Thumbnails (Full Disk Access)… |

Each menu item opens System Settings at the correct page. Turn on LivePointer in that page.

## 5. Pair the iPhone with the Mac

Pair once. The iPhone remembers the Mac.

1. Open LivePointer on the iPhone. The Nearby Macs screen shows the Macs on the network.
2. Tap your Mac.
3. The iPhone shows a safety code. The Mac shows the same code in its pairing window. Make sure that the two codes are the same.
4. Tap Pair.

Alternative: scan the code.

1. On the Mac, click the menu bar icon. Click Show Pairing Code…
2. On the iPhone, tap Scan code. Point the camera at the Mac's screen.

Alternative: type the name.

1. On the iPhone, tap Enter name.
2. Type the Mac's network name, for example `macbook.local`.

Note: When the iPhone does not find the Mac, tap Allow Local Network access, then Open Settings. Turn on Local Network for LivePointer.

## 6. Point

1. Hold the iPhone sideways. The preview of the Mac's display fills the screen.
2. Touch the preview at the spot that you want to show. The pointer appears at the same spot on the Mac's display.
3. Move your finger. The pointer follows.
4. Lift your finger. The pointer disappears.

The pointer has three styles:

- Dot. A red dot.
- Spotlight. The display becomes dark, except for a circle around your finger.
- Ink. A line that follows your finger. The line disappears after a short time.

To change the style:

1. Tap the ⋯ button at the top left. The style bar opens.
2. Tap Dot, Spotlight or Ink.
3. Tap the ⋯ button again. The style bar closes.

To change the size while you point, put two fingers on the preview. Move the fingers apart to make the pointer larger. Move the fingers together to make it smaller.

To change the size, the colour or the display, tap Settings in the style bar.

## 7. Change slides

Start the show in PowerPoint or Keynote on the Mac, as usual. Then use one of these controls.

| Control | Next slide | Previous slide |
|---|---|---|
| On the screen | Tap the › area on the right | Tap the ‹ area on the left |
| Volume buttons, while the app is open | Volume down | Volume up |
| Action Button | Press it | — |
| Back Tap | Tap the back of the iPhone two times | Tap it three times |
| Shortcuts | The Next Slide action | The Previous Slide action |

The Action Button and Back Tap also work when the iPhone is locked. Set them up one time in the iPhone's Settings app: Settings > Action Button, or Settings > Accessibility > Touch > Back Tap. Choose the LivePointer shortcut.

To start or stop the show from the iPhone, tap Start show or End show in the style bar. End show asks for a second tap.

Note: On a Mac with two displays, Start show from the iPhone works when PowerPoint is the front app on the Mac. When it is not, the iPhone shows a message. Click PowerPoint on the Mac, then tap Start show again.

## 8. Jump to a slide

1. Move three fingers up on the preview. The slide strip opens at the bottom. The strip shows a thumbnail of each slide.
2. Tap a thumbnail. The iPhone shows it large, with a Show button.
3. Tap Show, or tap the thumbnail a second time. The Mac shows that slide.

You can also tap the Slides tab at the bottom of the screen to open the strip. To close the strip, touch the slide.

In Settings, Slide thumbnails has three positions:

- Off. The Mac does not read the deck.
- Tap to show. The strip opens from the tab, or with three fingers.
- Always on. The strip stays on the screen.

When the thumbnails are off, type a slide number in the Slide # field and tap Go.

## 9. Gestures

| Gesture | Result |
|---|---|
| One finger | Point |
| Two fingers, apart or together | Change the pointer size |
| Three fingers, up | Open the slide strip |
| Three fingers, down | Open the style bar |
| Tap ⋯ | Open or close the style bar and the strip |

## 10. Demo mode

You can try the controller without a Mac. On the Nearby Macs screen, tap Try a demo. The demo shows a sample slide. All the controls work. Nothing is sent over the network.

## 11. Problems

| Problem | Cause | Action |
|---|---|---|
| No Mac in the list | Local Network access is off, or the devices are on different networks | Turn on Local Network for LivePointer. Put both devices on the same Wi-Fi, or use the iPhone's hotspot. |
| "Can't reach" with Choose another Mac | The Mac was renamed, or it is off | Tap Choose another Mac. Pair again. |
| Certificate changed | LivePointer on the Mac was reset or reinstalled | Make sure that the safety codes are the same. Then pair again. |
| Preview is off on the Mac | Screen Recording is off, or the preview is not sent | Enable Screen Preview on the Mac. Make sure that Send Screen Preview to iPhone has a tick. |
| Slide keys not enabled on the Mac | Accessibility is off | Enable Slide Keys on the Mac. |
| Slide thumbnails need Full Disk Access | Full Disk Access is off | Enable Slide Thumbnails on the Mac. Open the deck again. |
| The pointer is in the wrong place | The pointer is on a different display | In Settings, choose the display under Show the pointer on. |

To start again from zero, click the menu bar icon on the Mac and click Reset Pairing…. Then pair the iPhone again.

## 12. Privacy

LivePointer has no account, no analytics and no tracking. The iPhone and the Mac talk directly, with encryption. The camera is used only to scan the pairing code. See the privacy policy: https://github.com/JH-Eric-Yang/LivePointer/blob/main/PRIVACY.md

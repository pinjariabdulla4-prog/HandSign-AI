# HandSign AI

**Real-time Hand Sign Recognition Web App**

HandSign AI is a browser-based assistive communication prototype. It uses a device camera to track hands, display hand landmarks, identify selected hand poses, and help users compose and speak short messages.

## Features

- Live camera preview with front/rear camera switching.
- Hand landmark tracking for up to two hands.
- Gesture and hand-pose feedback with an on-screen result and confidence estimate.
- Quick communication phrases.
- Message builder with undo and clear controls.
- Text-to-speech for speaking a composed message.
- Speech-to-text where supported by the browser.
- Recent activity history.
- Emergency dialer shortcuts for India: 112, 100, and 108.
- Trusted-contact call and prepared SMS shortcuts.

## Technology

- HTML5, CSS3, and JavaScript (ES modules)
- MediaPipe Tasks Vision (Hand Landmarker and Gesture Recognizer)
- Browser camera access through `getUserMedia`
- Web Speech APIs for speech output and supported speech input
- GitHub Pages for hosting

## Run the project

1. Open the deployed website: https://pinjariabdulla4-prog.github.io/HandSign-AI/
2. Use a modern browser such as Google Chrome.
3. Allow camera access when prompted.
4. Select **Start camera** and hold a hand clearly in view.
5. Use the phrase buttons or message builder to compose a message.
6. Select **Speak** to read the message aloud.

For camera access, open the website over HTTPS and make sure the browser and phone settings allow camera permission.

## Repository files

- `index.html` — main website (HandSign AI V4).
- `HandSign-AI-Professional-V4.html` — separate copy of the V4 release.
- `manifest.json` — Progressive Web App manifest.
- `sw.js` — service worker.
- `icon-192.png` and `icon-512.png` — app icons.

## Important scope and limitations

HandSign AI is an assistive communication prototype, not a certified sign-language interpreter. Hand tracking and selected pose feedback do not equal full sign-language translation. The current project does **not** claim complete A–Z ISL/ASL alphabet recognition or reliable sentence-level sign-language translation.

Gesture labels and pose estimates may be affected by lighting, camera angle, hand position, and browser/device performance. Speech input availability varies by browser.

Emergency shortcuts open the phone's dialer or messaging app. The user must confirm the call or message on the device. HandSign AI is not an emergency service.

## Project links

- Repository: https://github.com/pinjariabdulla4-prog/HandSign-AI
- Live website: https://pinjariabdulla4-prog.github.io/HandSign-AI/

---
Made as a diploma project prototype focused on accessible communication.

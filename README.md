# Adaptive UI Modality Engine

A pastel-themed web page that **detects how you are using it** (mouse, touch, pen, keyboard or voice) and **reshapes itself in real time**. Buttons grow for fingers, stay compact for mouse, and show a bold focus ring for keyboard users.

Built as a single HTML file. No libraries, no installs.

---

## Features

- **Input detection:** Mouse, touch, pen, keyboard and voice are detected automatically.
- **Adaptive components:** Buttons, text box and toggle change size and focus style for each input type.
- **Device detection:** Shows whether the page is open on a computer or a mobile/tablet.
- **Voice control:** Say a command to change the box (see the list below).
- **Gesture control:** Drag the box with a mouse, finger or pen.
- **Mode control:** Auto mode, or force a mode for testing.
- **Live stats:** Counts how many times each input mode was used.
- **Switch history:** Shows the last 5 mode changes with time.
- **Accessibility:** Screen-reader announcements and reduced-motion support.

---

## How it works

| Input | What the page does |
|-------|--------------------|
| Mouse | Compact, precise layout |
| Touch | Large buttons for fingers |
| Pen | Medium-sized buttons |
| Keyboard | Thick gold focus ring |
| Voice | Voice mode badge and box control |

The page uses **Pointer Events** to tell mouse, touch and pen apart, key events for keyboard, and the **Web Speech API** for voice.

---

## Voice commands

Press **Start Voice Control** and say one of these:

| Command | What it does |
|---------|--------------|
| red, blue, green, pink, gold | Changes the box colour |
| bigger | Makes the box larger |
| smaller | Makes the box smaller |
| reset | Puts the box back to its starting colour, size and position |

Voice works in Chrome and Edge and needs microphone permission.

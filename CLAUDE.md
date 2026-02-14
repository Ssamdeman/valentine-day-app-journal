# What We're Building

A one-time-use mobile Valentine's date invitation journey. 
Single index.html. No frameworks. GSAP via CDN. GitHub Pages.

## Flow
Screen 1 → Screen 2 → Screen 3 → Screen 4 → Screen 5
No back navigation. Each screen slides up and replaces previous.
Progress shown as 5 dots at top.

## Screen 1 — The Ask
- Animated tree of hearts growing from bottom on load
- Text fades in: "hey you..." then "Will you be my Valentine?"
- YES button: large, glowing, bottom center, pulsing
- NO button: small, when tapped it runs away randomly on screen
  After 3 dodges it disappears and YES glows brighter
- On YES: heart particle burst → transition to Screen 2

## Screen 2 — Pick a Movie
- Header: "first things first..." / "Pick our movie"
- 3 vertical cards, staggered float-up entrance
- Each card: poster image, title, vibe tag
- Tap: 3D flip reveals short description, card glows, locks in
- Unselected cards fade out, auto-advance after 1.2s

## Screen 3 — Pick a Wine
- Header: "now the important part..." / "What are we drinking?"
- Same card mechanic as Screen 2
- Each card: image, wine name, flavor note
- Auto-advance after selection

## Screen 4 — Pick the Food
- Header: "almost there..." / "What are we eating?"
- 3 cards, can select multiple (min 1)
- Selected items appear as thumbnails in a sticky bottom "plate"
- "Order It 🛒" button — disabled until 1 selected
- On tap: opens placeholder link in new tab → advances to Screen 5

## Screen 5 — The Reveal
- Dark cinematic fade-in entrance
- "it's official..." / "Our Date Night ✨"
- Summary card showing all choices made
- Personal message placeholder
- Countdown timer to placeholder date
- "Screenshot this 📸" hint button

## All images are placeholders using picsum.photos
## All links are # placeholders
## All personal text is clearly marked PLACEHOLDER
```

# Happy Mother's Day — Interactive Gift Website

A beautiful, animated Mother's Day surprise built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just open and share! 🌸

## Live Demo

🔗 https://nabeela-fatima.github.io/mothers-day-gift/

## What's Inside

A 10-screen interactive journey made with love:

| Screen | Description |
| Landing | Animated cat character with a warm welcome |
| Rainbow | Animated rainbow arcs drawing in one by one |
| Memory | Two personal photos connected by a flowing line |
| What You Mean | Tap the heart to reveal floating love tags |
| Timeline | Scroll-animated journey from 2006 to today |
| Crown | Girl climbs a ladder to crown Mom as the best |
| WOW / MOM | Flip animation — MOM upside down spells WOW! |
| Candle | Light a candle — "You light up my world" |
| Letter | Open an envelope to read a heartfelt letter |
| Final | Floating hearts and a Mother's Day message |

## Project Structure

mothers-day-gift/
├── index.html       ← entire website (single file)
├── photo1.jpeg      ← memory screen photo 1
├── photo2.jpg       ← memory screen photo 2
├── photo3.jpg       ← letter screen photo
└── README.md


## How to Run Locally

No setup needed — just open the file:

# Clone the repo
git clone https://github.com/Nabeela-Fatima/mothers-day-gift.git

# Open in browser
open index.html

Or just double-click `index.html` in your file explorer.

## Built With

- **HTML5** — structure and content
- **CSS3** — animations, transitions, gradients
- **Vanilla JavaScript** — screen navigation, interactivity
- **Google Fonts** — Poppins typeface
- **SVG** — all illustrations drawn inline (no image assets for characters)

## Replacing Photos
To personalise with your own photos, replace these files in the repo root:

| File | Used In |
|------|---------|
| `photo1.jpeg` | Memory screen — top photo |
| `photo2.jpg` | Memory screen — bottom photo |
| `photo3.jpg` | Letter screen — profile photo |

Keep the same filenames, or update the `src` paths in `index.html`.

## Personalisation Tips

Open `index.html` and search for these to customise:

- **Name** → search `Nabeela` and replace with your name
- **Letter text** → search `Dear Mamma` to edit the letter body
- **Timeline events** → find the `TL` array in `screenTimeline()`
- **Love tags** → find the `TAGS` array in `screenWhatYouMean()`


## Mobile Friendly
Designed for mobile screens (max-width 430px) but works on desktop too. Best experienced on a phone — send the link to your mom and let her tap through it! 

## Made With Love

> *"You are rainbow in my clouds."*

Made for Mamma — with all my heart.

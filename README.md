# Japan 2026 — Trip Preparation Guide

A single-file personal study and travel preparation guide built with Claude (Anthropic) for a Smithsonian Journeys "Eternal Japan" tour departing **August 31, 2026**, including the optional Hiroshima extension.

---

## What the page contains

### 1. 14-Week Study Guide
42 study sessions (3/week, ~18 min each), organized by the actual stops on the itinerary. Each session has a direct link to a free article or YouTube video. Topics progress from Japanese history foundations → Tokyo → Mt. Fuji → Kanazawa → Kyoto → Hiroshima & WWII → contemporary Japan. Emphasis on art, culture, and religion. Weeks are collapsible.

### 2. Packing Context Sheet
Not a generic packing list, but the cultural and practical *why* behind what to bring for Japan specifically in early September (heat/humidity/typhoon season, temple etiquette, ryokan customs, cash culture, etc.).

### 3. Essential Japanese Phrases
15 phrases with Japanese script, romanization, usage notes, and a 🔊 speaker button that uses the browser's Web Speech API to play each phrase in a female Japanese voice (no internet required for audio).

### 4. What You'll See at Each Stop
A preview card for every destination: Tokyo, Mt. Fuji/Lake Suwa, Takayama, Kanazawa, Kyoto/Nara, and the Hiroshima/Miyajima extension.

---

## Technical notes

- Pure HTML/CSS/JS — no frameworks, no build step, no dependencies to install
- Google Fonts (Noto Serif JP, DM Sans, DM Mono) loaded from CDN — requires internet to render correctly
- All study guide links go to free, publicly accessible resources
- Speech synthesis uses the browser's built-in Web Speech API — prefers female Japanese voices (Kyoko on Apple devices, Nanami/Haruka on Windows)
- Countdown to departure date is calculated live from today's date

## How to deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `japan-2026`)
2. Upload `index.html` (rename from `japan-trip-guide.html`)
3. Go to **Settings → Pages → Source** and select `main` branch, root folder
4. Your guide will be live at `https://yourusername.github.io/japan-2026` within ~1 minute

---

## How to recreate or extend this in Claude

Start a new Claude conversation and paste the following:

> "I have an existing Japan trip guide as a single HTML file (`index.html`), built to help me prepare for a Smithsonian Journeys Eternal Japan tour departing August 31, 2026, including the Hiroshima extension. The file contains: a 14-week study guide (42 sessions, 3/week, ~18 min each) organized by destination with links to free articles and videos; a packing context sheet specific to Japan in early September; a phrases table with 15 Japanese phrases and a Web Speech API speaker button for female Japanese voice playback; and a stop-by-stop preview of the itinerary. I'd like to [describe what you want to add or change]."

Then upload the current `index.html` file so Claude can read it directly and modify it.

---

## Tour itinerary reference

| Days | Destination | Key stops |
|------|-------------|-----------|
| 2–4 | Tokyo | Senso-ji, Edo-Tokyo Museum, Imperial Palace, calligrapher gallery |
| 5 | Mt. Fuji / Lake Suwa | Hakone-Izu National Park, ryokan overnight, onsen |
| 6 | Takayama | Old town Sanmachi Suji, Hida Folk Village |
| 7–8 | Kanazawa | Kenrokuen Garden, geisha district, gold leaf gallery |
| 9–12 | Kyoto | Nijo Castle, Kinkaku-ji, Fushimi Inari, tea ceremony, Nara day trip |
| Extension | Hiroshima + Miyajima | Peace Memorial Museum, Atomic Bomb Dome, Itsukushima Shrine |
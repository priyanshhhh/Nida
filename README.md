# her.

> *"I overthink everything. But thinking about you never felt like a problem. It felt like the only thing I was doing right."*

A personal, handcrafted single-page web experience — part love letter, part poetry collection, part confession. Built in pure HTML, CSS, and vanilla JavaScript. No frameworks. No libraries. Just words and a dark screen.

---

## what this is

**her.** is a single HTML file that tells a story — mine.

It began as something private. A place to put feelings that had nowhere else to go. It turned into something I actually built carefully, obsessively, the way you do when the subject matters more than you can explain.

The page contains:

- An origin story — how we met inside a Free Fire lobby, accidentally, through a friend group, through a block, through a second chance
- A love list — everything about her I keep
- Poems — 40+ original fragments, raw and structured, in English and Hindi
- A section about who I am — the hostel years, the anxiety, the panic attacks, the before and the after
- A letter I never sent to my father
- A closing that says exactly where I stand

It is not trying to be a portfolio piece. It is trying to be honest.

---

## preview

```
dark background  ·  warm dust & rose palette  ·  serif fonts
floating particles  ·  custom cursor  ·  scroll progress bar
ambient sound toggle  ·  scroll-triggered reveal animations
bilingual — English + Hindi/Urdu
```

---

## features

| Feature | Detail |
|---|---|
| **Zero dependencies** | Pure HTML + CSS + JS, no frameworks |
| **Single file** | Everything lives in `her.html` |
| **Custom cursor** | Dot + trailing ring, `mix-blend-mode: difference` |
| **Particle system** | Canvas-based floating dust particles |
| **Scroll animations** | IntersectionObserver reveal on every section |
| **Ambient sound** | Web Audio API — layered sine drones + soft noise |
| **Reading progress** | Fixed top bar tracking scroll position |
| **Counting animation** | Stat number counts up on scroll into view |
| **Love list stagger** | Each list item animates in with delay |
| **Film grain overlay** | SVG noise texture via CSS `::after` pseudo-element |
| **Responsive** | Works on mobile, tablet, desktop |
| **Bilingual** | English + Devanagari (Noto Serif Devanagari) + Urdu romanized |

---

## fonts used

- [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) — headings, titles, large quotes
- [EB Garamond](https://fonts.google.com/specimen/EB+Garamond) — body text, poems
- [Noto Serif Devanagari](https://fonts.google.com/specimen/Noto+Serif+Devanagari) — Hindi sections

All loaded via Google Fonts.

---

## color palette

```css
--bg:      #07060a   /* near black background */
--dust:    #c4a882   /* warm gold — primary accent */
--rose:    #b87070   /* muted rose — emotional highlights */
--pale:    #ede4d8   /* off-white — body text */
--dim:     #6e6058   /* muted brown — secondary text */
--dimmer:  #3d3530   /* very dim — labels, timestamps */
```

---

## structure

The page flows in this order:

```
Hero
  └── origin story — how it began
  └── before it got complicated — warmth
  └── who she actually is
  └── love list

Poetry I — the fall begins

Hindi / Urdu section

Poetry II — obsession

Who she named — the Priyansh / Proo section

Poetry III — to her · december · coming home

About me — the boy who never came home
  └── hostel years (poems)
  └── panic / anxiety (poems)
  └── before · after

Letter to Papa

Healing · Love · Self-reflection · Final fragments

Closing
```

---

## how to run

No build step. No installs. Just open it.

```bash
# clone the repo
git clone https://github.com/yourusername/her.git

# open in browser
open her.html
```

Or just double-click `her.html`. That's it.

> **Note:** Ambient sound requires a user interaction (click the ♩ sound button) due to browser autoplay policies. Fonts require an internet connection to load from Google Fonts.

---

## file size

| | |
|---|---|
| `her.html` | ~100kb |
| External dependencies | Google Fonts only |
| Images | None |
| JS libraries | None |

---

## why I made this

I needed somewhere to put it.

I grew up in a hostel. I don't mix well with people. I have panic attacks and social anxiety and I talk to myself more than I talk to anyone. And then I met someone — inside a game, accidentally, in a friend group lobby — and she made the quiet in my head go away.

This page is about her. And about what I was before her. And about the fact that I don't plan on moving on.

---

## license

This code is open to read and learn from.

The words are mine. Please don't reuse the personal writing — the poems, the letters, the story — as your own.

---

*written in winter · 2024 · somewhere between 3am and always*

— Priyansh


# Ready Prompts — Istiak Ahmed Enan (SecureXone)

Copy-paste these into Claude / ChatGPT / Gemini. Attach your photo (`assets/profile-card.png`) where mentioned.

---

## 1) Animated portrait SVG (like the "profile.sh --live" card)

```
Attach: my photo.

Create ONE self-contained animated SVG file named portrait.svg for my GitHub profile README.

About me:
- Name: Istiak Ahmed Enan (brand: "Cyber Istiak")
- Role: Social Media Recovery Specialist | Cyber Security | Founder of SecureXone
- Location: Sherpur, Bangladesh
- Tagline: "Recover. Protect. Grow." and "Let's rebuild your online presence."
- Website: istiakahmedenan.site | Gmail: secistiak@gmail.com | WhatsApp: +8801902936977

Design:
- Size 1180x560, rounded corners, dark background (#050B05) with a faint grid.
- Neon lime accent (#B6FF00) + white + gray. Monospace font.
- Left: my photo (embed as base64 inside the SVG, rounded frame) with an animated lime border that draws itself, plus a slow vertical scan-line glow passing over the photo.
- Right: a terminal window (red/yellow/lime dots) that "types" these lines one by one using SMIL <animate> + clipPath, then shows a blinking cursor:
  $ whoami -> istiak_ahmed_enan
  $ cat role.txt -> Social Media Recovery Specialist / Cyber Security | Founder @ SecureXone
  $ cat location.txt -> Sherpur, Bangladesh
  $ ./mission.sh -> RECOVER > PROTECT > GROW
- Add a soft pulsing lime radial glow behind everything.
- Rules: NO JavaScript, NO external images/fonts (GitHub blocks them). Use only SMIL/CSS animation. File under 300 KB. Must render on GitHub in dark and light mode.
Return only the SVG code.
```

---

## 2) ASCII-art animated portrait (exact style of the reference repo)

```
Attach: my photo.

Convert my photo into an ASCII-art portrait and build an animated SVG terminal card (1180x610) titled "Istiak Ahmed Enan — profile.sh --live".
- Left: ASCII portrait made of monospace characters, colored with an animated vertical gradient (lime #B6FF00 -> green #84CC16 -> white), shimmer moving top to bottom every 9s.
- Right: terminal panel with typed lines: name, role (Social Media Recovery Specialist), company (SecureXone), location (Sherpur, Bangladesh), skills (Account Recovery, Cyber Security, Digital Protection), contact (istiakahmedenan.site).
- Make TWO files: portrait_dark.svg (dark bg #0A0F0A) and portrait_light.svg (light bg #FFFFFF, darker green #4D7C0F text).
- SMIL animations only, no JavaScript, no external resources.
```

---

## 3) Animated banner (like konam-shivamani-banner)

```
Create an animated SVG banner, 1600x635, for my GitHub profile.
Text: "ISTIAK AHMED ENAN" (large), subtitle "SecureXone — Recover • Protect • Grow".
Style: dark green/black gradient background, flowing neon-lime (#B6FF00) wave lines animated with SMIL, subtle floating particles, and an "SX" logo mark at the left.
No JavaScript, no external assets. Return only the SVG.
```

---

## 4) SecureXone "SX" logo (SVG)

```
Design a modern logo for "SecureXone" as an SVG: bold italic letters "SX" in neon lime (#B6FF00) on transparent background, the X formed by two sharp slashes, with a small shield/lock hint inside the X. Also give a dark-background version and a light-background version. Clean vector, under 5 KB each.
```

---

## 5) Re-generate the full README (if you want to change it later)

```
Write a stunning GitHub profile README.md for username "istiakahmedenan" in this structure:
animated typing header -> animated portrait.svg -> social badge row (Website, LinkedIn, Facebook Page, WhatsApp, Gmail, GitHub — with logos) -> About Me -> What I Do -> SecureXone company section -> Tech & Tools badges -> GitHub stats (streak, stats, top languages, dark/light <picture>) -> contribution snake -> Contact table -> footer wave.
Theme: dark with neon lime (#B6FF00). Use shields.io, skillicons.dev, readme-typing-svg, github-readme-stats, streak-stats.demolab.com, capsule-render.
My details:
- Istiak Ahmed Enan, born 2006, from Sherpur, Bangladesh
- Social Media Recovery Specialist, cyber security, founder of SecureXone
- GitHub: https://github.com/istiakahmedenan
- Facebook page: https://www.facebook.com/share/1Gx5j5gvok/?mibextid=wwXIfr
- LinkedIn: https://www.linkedin.com/in/istiak-ahmed-enan-15005a3a2
- WhatsApp: +8801902936977 | Gmail: secistiak@gmail.com | Website: istiakahmedenan.site
Write everything in polished English.
```

---

## How to publish

1. On GitHub create a **public** repo named exactly `istiakahmedenan` (same as your username).
2. Upload everything in this folder (`README.md`, `portrait.svg`, `assets/`, `.github/`).
3. Go to **Actions → Generate Snake Animation → Run workflow** once (creates the snake).
4. Open your profile page — the README shows on top.

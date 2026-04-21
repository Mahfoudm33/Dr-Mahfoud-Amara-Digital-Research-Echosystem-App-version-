# Dr. Mahfoud Amara — Digital Research Ecosystem

> *Bridging global and local knowledge systems — combining critical theoretical insight with empirical depth to reposition sport as a key site for understanding power, identity, and geopolitical transformation in the MENA region and beyond.*

---

## Overview

This repository hosts the **Digital Research Ecosystem** of Dr. Mahfoud Amara, Associate Professor of Sport Social Sciences and Management at the College of Sport Sciences, Qatar University.

The ecosystem is a network of five interconnected GitHub Pages platforms, unified through a central hub application (`index.html`). It functions as an open, publicly accessible scholarly infrastructure — bringing together research outputs, thematic platforms, media coverage, and academic resources in a single navigable interface.

The project reflects a commitment to **open knowledge**, **digital dissemination**, and the democratisation of sport scholarship across Arabic, English, and French academic traditions.

---

## Live Site

```
https://mahfoudm33.github.io
```

---

## File Structure

```
mahfoudm33.github.io/
│
├── index.html          ← Main hub application (self-contained)
├── README.md           ← This file
└── assets/
    └── amara.jpg       ← Portrait photo (add when ready — see below)
```

---

## The Five Research Platforms

| # | Platform | Geographic Focus | Theme |
|---|----------|-----------------|-------|
| 01 | **The Corniche Walk** | Qatar · GCC | Sport, culture and everyday life in the Gulf |
| 02 | **Sport & Algerian Studies** | Algeria · North Africa | Postcolonial sport, national identity and historical narrative |
| 03 | **Sport in the Arab World** | Arab World (regional) | Governance, media and geopolitics of Arab sport |
| 04 | **Sport in Islam** | Muslim communities globally | Ethics, gender and embodied practice |
| 05 | **The Peninsula Archive** | Cross-regional | Media archive — press, broadcast and public discourse |

Each platform operates as an independent GitHub Pages site and is accessible from the central hub.

---

## Research Themes

The ecosystem is organised around five core scholarly themes:

1. **Sport, power and geopolitics** — Regional agency, soft power, sportswashing critique, mega-events (FIFA World Cup 2022, AFCON, Olympics). Key frameworks: Nye (soft power), Bourdieu (field theory), political economy of sport.

2. **Sport, identity and nation-building** — Biographical and socio-historical methods, MENA nationalisms, Algeria, Morocco, Gulf states. Key frameworks: biographical method, historical sociology, Elias (figuration theory).

3. **Media, discourse and counter-narratives** — Critical discourse analysis, framing theory, Orientalism critique, Arab media. Key frameworks: CDA, Said, postcolonial theory.

4. **Sport development, ethics and governance** — Anti-doping policy, WADA, IOC, mega-event legacies, sport integrity, GCC governance. Key frameworks: governance theory, policy analysis.

5. **Gender and local epistemologies in MENA** — Decolonial feminism, women in sport, Muslim women, local epistemologies. Key frameworks: Sehlikoglu, Chakrabarty, decolonial feminism, critical theory.

---

## Technology

The hub application is built as a **single self-contained HTML file** — no build tools, no frameworks, no dependencies beyond Google Fonts.

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties, grid, flexbox, animations
- **Vanilla JavaScript** — panel navigation, no libraries required
- **Google Fonts** — Cormorant Garamond (display) · DM Sans (body)
- **GitHub Pages** — zero-configuration static hosting

This architecture was chosen deliberately: it is portable, version-controllable, fast-loading, and requires no server-side infrastructure.

---

## Deployment

### Initial setup

1. Clone or fork this repository
2. Ensure GitHub Pages is enabled: `Settings → Pages → Source: main branch / root`
3. The site goes live at `https://[username].github.io` within minutes

### Updating content

All content lives directly in `index.html`. To update:

1. Open `index.html` in any text editor
2. Locate the relevant section (platforms, research, profile, connect)
3. Edit the content between the HTML tags
4. Commit and push — GitHub Pages deploys automatically

### Adding your portrait photo

1. Place your photo file in `/assets/amara.jpg`
2. Open `index.html` and find the commented block at the bottom of the `<script>` tag
3. Uncomment those lines — the image will render automatically
4. Commit and push

### Updating platform URLs

When each sub-platform repo is ready, update the `href` attribute on each platform card link in `index.html`:

```html
<!-- Before -->
<a class="platform-link" href="https://mahfoudm33.github.io" target="_blank">

<!-- After (example) -->
<a class="platform-link" href="https://mahfoudm33.github.io/corniche-walk" target="_blank">
```

---

## Embedding in an Existing Page

To embed the app inside an existing GitHub Pages site rather than replacing the index:

```html
<!-- Option A: iframe embed -->
<iframe
  src="https://mahfoudm33.github.io"
  width="100%"
  height="700px"
  style="border: none;"
  title="Dr. Mahfoud Amara — Digital Research Ecosystem">
</iframe>

<!-- Option B: paste the contents of index.html directly
     into the <body> of your existing page,
     adjusting any conflicting CSS custom properties -->
```

---

## Academic Context

**Dr. Mahfoud Amara** is a transnational bridge scholar operating across Algeria / North Africa, the UK / Western academia, and Qatar / the Gulf. His work functions as knowledge brokerage — translating concepts across Arabic, English, and French academic traditions and foregrounding locally grounded interpretations of sport in Arab and Muslim societies.

### Institutional roles

- Associate Professor of Sport Social Sciences and Management, Qatar University
- Reviewer, IOC Olympic Studies Centre Grants Committee
- External Examiner, Loughborough University (UK)
- External Examiner, University of Bordeaux (France)
- Invited Speaker, University of Michigan (USA)
- Institutional collaborator — QADA · QOC
- Research funding reviewer — Canada · Netherlands

### Selected media coverage

Al Jazeera · Le Monde · BBC · La Vanguardia · The Conversation

### Languages of scholarship

English · العربية · Français

---

## Roadmap

- [ ] Add portrait photo to `/assets/`
- [ ] Update platform card URLs with confirmed sub-platform links
- [ ] Add Publications panel with full bibliography
- [ ] Add Arabic (RTL) language toggle
- [ ] Add Promotion Dossier summary panel
- [ ] Connect The Peninsula Archive media timeline

---

## Licence

All original content © Dr. Mahfoud Amara, Qatar University.  
Code structure is open for reuse and adaptation under [MIT Licence](https://opensource.org/licenses/MIT).  
Academic content, research descriptions, and biographical material remain the intellectual property of the author.

---

*Last updated: April 2026*


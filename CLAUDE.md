# Instructies voor Claude Code — Skager website (ontwerp 2b)

## Context
Tweetalige statische site (pure HTML, inline styles + /assets/responsive.css) voor Skager BV.
NL in de root, EN onder /en/ met eigen slugs (services, approach, about, contact).
Live op skager.eu via Cloudflare Pages; push naar `main` = automatische deploy.

## Huisstijl (2b)
- Achtergrond licht `#f8f9f9` / secties `#eef2f2`; navy `#1C3B5E`; blauwgroen `#3E8E9E`;
  secundaire tekst `#41597A`; hover-accent `#2B6898`.
- Typografie: koppen in **Cormorant Garamond** (500), lopende tekst **Jost** (300/400),
  labels/kickers in **IBM Plex Mono**. Ruime letter-spacing op SKAGER-woordmerk (.3em).
- Toon: zakelijk, kalm. NL: u-vorm. EN: professioneel Brits-neutraal Engels.

## Regels bij wijzigingen
1. NL en EN zijn spiegels van elkaar: elke inhoudelijke wijziging in beide talen doorvoeren.
2. Behoud de inline-style-aanpak; nieuwe secties volgen bestaande patronen.
3. Navigatie en footer identiek houden op alle pagina's van dezelfde taal;
   de taalwissel in de nav verwijst altijd naar de equivalente pagina in de andere taal.
4. Paden altijd absoluut (`/assets/...`, `/en/...`). Canonical/hreflang-tags meenemen bij nieuwe pagina's.
5. Controleer na wijzigingen links, assets en mobiele weergave (responsive.css < 960/720px).
6. Publiceer nooit interne documenten in deze repo. Commits in het Nederlands.

# Skager — website (skager.eu)

Tweetalige statische website (NL/EN) voor Skager BV — ontwerp "2b" (licht, Cormorant Garamond + Jost).
Gehost via Cloudflare Pages; elke push naar `main` deployt automatisch.

## Structuur
- Nederlands (root): `index.html`, `diensten.html`, `aanpak.html`, `over.html`, `contact.html`
- Engels: `en/index.html`, `en/services.html`, `en/approach.html`, `en/about.html`, `en/contact.html`
- `assets/` — logo's, favicons en `responsive.css` (mobiele laag)

Alle paden zijn absoluut (`/assets/...`), SEO is geregeld met canonical + hreflang-tags per taalpaar.

## Pages-instellingen
Build command: *(leeg)* · Build output directory: `/`

## Onderhoud met Claude Code
Geef opdrachten in gewone taal ("voeg dienst X toe", "werk de Engelse contactpagina bij").
Wijzig NL- en EN-versies altijd samen. Zie `CLAUDE.md` voor de huisstijlregels.

## Open punten
- [ ] KvK-vermelding op de contactpagina invullen zodra bekend.
- [ ] E-mail: info@skager.eu instellen via Cloudflare Email Routing.

# Inspo — Juwelier Akbulut & Koc (Branche: Juwelier / Gold- & Brillantschmuck)

> **Limited inspo** — Dribbble via Playwright MCP nicht erreichbar (Server nicht verbunden), echter Chrome für Dribbble durch Cloudflare-Automation-Wall unzuverlässig. Synthese basiert auf etablierten Luxury-Jewelry-Editorial-Patterns (Cartier / Tiffany / Bucherer / unabhängige Goldschmiede-Brands). Patterns sind genre-konform und FlowState-eigenständig adaptiert.

## Übergeordnete Richtung
Editorial-Luxus mit warmer Gold-auf-Dunkel-Palette. Die Marke ist seit 1993 etabliert, 5,0 ★, eigene Goldschmiede-Werkstatt — also „Heritage-Handwerk trifft moderne Auswahl". Die Site soll ruhig, edel und großzügig wirken: viel Negativraum, große Serif-Display-Headlines, feines Gold als einziger Akzent, cinematische Low-Key-Produktbilder. Kein Glitzer-Kitsch — Zurückhaltung signalisiert Wert. Trauringe + Sonderanfertigung sind emotionale Anker, Goldankauf der vertrauensbildende Service.

## Referenzen (adaptierte Genre-Patterns)

### 1. Heritage Goldsmith — editorial dark
- Stil: editorial dark serif, warm gold accent, generous whitespace
- Übernehmen:
  - Asymmetrischer Hero: Full-bleed Produktbild mit innerem Gold-Hairline-Border (inset), Overlay-Bar unten mit Material-Tags links + CTA rechts
  - „Seit 1993"-Heritage-Marker als Overline über der ersten Headline

### 2. Trauring-Maison
- Stil: romantic minimal, soft serif, paired-rings motif
- Übernehmen:
  - Dedizierter Trauringe-Block mit ruhiger Doppel-Ring-Symbolik und „Ja"-Emotionalität
  - Roman-Numeral-Labels („I · Collier", „II · Trauring") für Signature-Stücke

### 3. Diamond Atelier
- Stil: low-key macro, sparkle-on-black, luxury magazine
- Übernehmen:
  - Brillant-Makro-Close-ups als Section-Übergänge
  - Duotone-Behandlung einer Bildgruppe für editoriale Kohärenz

### 4. Modern Boutique Jeweler
- Stil: clean grid, uppercase micro-labels, sticky blur header
- Übernehmen:
  - Sticky Header mit `backdrop-filter:blur`, Logo mittig, Nav L/R, runde Icon-Buttons
  - Kategorien als ruhiges 3–4-Spalten-Grid (Bild + Titel + Mini-Text)

### 5. Artisan Workshop Brand
- Stil: craftsmanship storytelling, hands-at-work, warm task light
- Übernehmen:
  - Atelier/Über-uns als Image-Text-Split mit Goldschmiede-Hände-Portrait (3:4)
  - Service-Trias Goldschmied · Reparatur · Sonderanfertigung als ruhige Feature-Reihe

### 6. Gold-Buyback Trust Section
- Stil: trust-forward, clear, warm
- Übernehmen:
  - Goldankauf als vertrauensbildender Block: „faire Bewertung, transparente Tagespreise"
  - Testimonials aus echten 5★-Reviews direkt darunter

## Konkrete Anpassungen für Phase 6
- **Font-Pair**: `Cormorant Garamond` (Display/Headlines, romantisch-edel, passt zu Trauring-Emotion) + `Inter` (Body, modern-neutral, ruhige Lesbarkeit). Begründung: Heritage-Eleganz + moderne Auswahl.
- **Hero-Treatment**: Full-bleed Gold-auf-Dunkelmarmor-Hero mit Inset-Gold-Hairline-Border (Ref 1), Ken-Burns, Overlay-Bar unten (Tags „Trauringe · Brillanten · Goldankauf" links, CTA „Kollektion entdecken" rechts).
- **Section-Flourishes**: Gold-Line-Divider (`.gold-line` mit beidseitigen Hairlines), Roman-Numeral Signature-Cards, Duotone auf der Detail-Galerie, dezente Marmor-Textur-Overlays.
- **Mikro-Interaktionen-Highlights**: Underline-Reveal Nav, Hover-Scale auf Gallery-Bildern, Fade-in-on-scroll (IntersectionObserver), Parallax auf einer Section.
- **Farb-Mood-Hinweis**: warm gold-auf-dunkel (kein Pastell) — wird final aus dem Hero extrahiert (Phase 4).

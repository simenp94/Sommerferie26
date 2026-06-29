# Sommerferie 2026 — Ischia & Napoli reiseplanlegger

En liten, frittstående nettapp for sommerferien på **Ischia (3.–10. august)** og i
**Napoli (10.–12. august)**. Bla i kuraterte spisesteder, vingårder, badeplasser,
terme og kultur, og fest dem til dagene i reiseruten. Planen lagres automatisk.

**Live:** https://simenp94.github.io/Sommerferie26/

---

## Hva appen kan

- **Utforsk** — alle stedene som kort, med filtre for sted (Ischia/Napoli), type
  (mat & vin, bad & dykk, terme & spa, kultur & natur), budsjett og **avstand fra
  hotellet** (≤10 min gange / ≤30 min gange / buss·båt·taxi). Hvert kort viser
  gangtid fra basen og lenke til Google Maps.
- **Min plan** — alle dagene 3.–12. august med riktig base markert. Legg til /
  fjern aktiviteter, se grovt prisanslag per dag, og bruk knappen
  **«Bruk anbefalt plan»** for et ferdig forslag du kan justere fritt.
- **Lagring** — planen lagres automatisk i nettleseren (knyttet til adressen over).

---

## Slik oppdaterer du appen (samme lenke hver gang)

Hele appen ligger i **én fil: `index.html`**. For å publisere en ny versjon:

1. Gå til repoet på github.com → åpne `index.html`.
2. Trykk blyant-ikonet (Edit) — eller **Add file → Upload files** og erstatt fila.
3. Skriv en kort commit-melding og trykk **Commit changes**.

Adressen forblir nøyaktig den samme, og hjemskjerm-appen viser den nye versjonen
neste gang den åpnes. Hver commit er et lagret versjonspunkt, så du kan rulle
tilbake hvis noe ble feil.

Foretrekker du git lokalt:

```bash
git add index.html
git commit -m "Oppdatert plan"
git push
```

---

## Legg appen på hjemskjermen

Åpne https://simenp94.github.io/Sommerferie26/ på telefonen:

- **iPhone (Safari):** Del-knappen → *Legg til på Hjem-skjerm*
- **Android (Chrome):** meny (⋮) → *Legg til på startskjerm* / *Installer app*

Du får et eget ikon (hav, korallsol og bølger) som åpner appen i fullskjerm.

---

## Godt å vite

- **Behold samme adresse.** Planen lagres i nettleserlagring knyttet til domenet.
  Bytter du URL, følger ikke den lagrede planen med over.
- **Oppdateringer dukker opp ved neste åpning.** Appen har ingen aggressiv
  mellomlagring. Ser den gammel ut en sjelden gang: dra ned for å oppdatere, eller
  lukk og åpne på nytt.
- **Krav til GitHub Pages:** repoet må være *Public*, `index.html` må ligge i roten,
  og Pages må være satt opp under Settings → Pages → *Deploy from a branch* →
  `main` / `/ (root)`.

---

## Filer i repoet

| Fil          | Hva det er                                  |
|--------------|---------------------------------------------|
| `index.html` | Hele appen (HTML, CSS, JS og ikon i én fil) |
| `README.md`  | Denne fila                                  |

---

*Stedene er hentet fra åpne kartdata og er ment som et utgangspunkt — sjekk alltid
åpningstider og book bord på forhånd i høysesong.*

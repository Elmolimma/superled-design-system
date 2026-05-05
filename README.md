# SuperLED Design System

SuperLED Oy — LED-valaistus, Kempele. Suomen laajin valikoima, yli 80 000 tilausta.

## Rakenne

```
superled-design-system/
├── tokens/
│   ├── colors.css          — Kaikki värit ja semanttiset aliakset
│   ├── typography.css      — Fontit, koot, painot
│   └── spacing.css         — Spacing, border-radius, varjot, max-leveydet
├── components/
│   ├── buttons.css         — CTA-painikkeet (primary, dark, outline, urgent)
│   ├── badges.css          — Tarjous-, uutuus-, B2B-merkit
│   └── cards.css           — Tuotekortit, hyötykortit, promokortit
├── templates/
│   ├── email/
│   │   └── contractor-newsletter.html   — Urakoitsijauutiskirjepohja
│   └── landing/
│       └── storage-service.html         — Varastopalvelun laskeutumissivu
└── assets/                 — Logot, ikonit, kuvat
```

## Brändivärit

| Väri | Hex | Käyttö |
|------|-----|--------|
| Keltainen | `#FFD527` | CTA, korostukset |
| Tumma hiili | `#3A3A3A` | Otsikot, taustat |
| Vaalea kerma | `#F5F3EE` | Sivutaustat |
| Oranssi | `#FF7D12` | Kiireellisyys, tarjoukset |

## Äänensävy

- Sinutellaan aina
- Lyhyet lauseet, aktiivimuoto
- Konkreettiset luvut: "samana päivänä", "yli 80 000 tilausta", "~30% halvempi"
- Pääslogan: **"Tuntee tunnelman"**

## Asiakassegmentit

1. **Sähköurakoitsijat** — B2B, tärkein, ~30% alennus, tekninen viestintä
2. **Sähkösuunnittelijat** — Vaikuttajat, helppous ja luotettavuus
3. **KWR-urakoitsijat** — Sekä suunnittelu että urakointi
4. **Remontoijat** — B2C, tunnelma ja helppous
5. **Rakentajat & Yritykset** — B2C/B2B hybridi

## Käyttö Claude.ai:ssa

Linkitä tämä repo Claude.ai:n design system -setupissa:
→ "Link code on GitHub" → `Elmolimma/superled-design-system`

Tämä antaa Claudelle täyden kontekstin bränditokeneista, komponenteista ja pohjista kun luot uusia materiaaleja.

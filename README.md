# Legalize CZ

### Česká legislativa v Markdownu, verzovaná pomocí Gitu.

Každý zákon je soubor. Každá novela je commit.

**18 337 zákonů** · **32 101 commitů** · **Aktualizace z e-Sbírky**

Součást projektu [Legalize](https://github.com/legalize-dev/legalize) · [legalize.dev](https://legalize.dev)

> **Early stage** — This repository is under active development. File structure, commit history, and content may undergo significant changes, including full regeneration.

## Začínáme

```bash
# Klonovat českou legislativu
git clone https://github.com/legalize-dev/legalize-cz.git

# Co říká článek 1 Ústavy?
head -80 cz/SB-1993-1.md

# Kolikrát byla Ústava novelizována?
git log --oneline -- cz/SB-1993-1.md

# Zobrazit diff konkrétní novely
git show <commit> -- cz/SB-1993-1.md
```

## Struktura

```
cz/                          ← Sbírka zákonů
  SB-1993-1.md               — Ústava České republiky
  SB-2009-40.md              — Trestní zákoník
  SB-2012-89.md              — Občanský zákoník
  SB-1992-586.md             — Zákon o daních z příjmů
  ...
```

## Zdroj dat

[e-Sbírka](https://e-sbirka.gov.cz) — oficiální elektronická sbírka zákonů České republiky.

## Licence

MIT

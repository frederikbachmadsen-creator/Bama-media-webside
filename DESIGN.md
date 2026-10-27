# Bama – design

Kort udgave til Impeccable. `../CLAUDE.md`, `brand/BRAND.md` og `brand/tokens.css` er de gældende regler. Er der uenighed, vinder de altid. Brug kun CSS-variablerne fra `tokens.css`, aldrig hårdkodede hex-værdier.

## Farver

| Token | Hex | Brug |
| --- | --- | --- |
| `--paper` | #FFFFFF | Sidebaggrund |
| `--surface` | #F4F6F3 | Kort, felter |
| `--tint` | #E7EBE5 | Afdæmpede sektioner, pladsholdere |
| `--line` | #D8DDD5 | Hårfine streger, kortrammer |
| `--ink` | #161A17 | Al tekst |
| `--ink-muted` | #565C58 | Sekundær tekst |
| `--accent` | #1A7F45 | Grøn: knapper, prikken, ét ord. Som tekst kun 24px+ |
| `--accent-deep` | #12603A | Links, lille accenttekst, hover |
| `--accent-bright` | #3DBA6E | Kun på Forest/mørke flader |
| `--forest` | #1F3A2F | Mørke flader (Om mig, abonnement, footer). Hvid tekst |
| `--butter` | #E7B547 | Ét fremhævet ord. Aldrig flader |

Fordeling ca. 70 % Paper/Surface/Tint, 15 % Ink, 10 % Forest, 5 % grøn/Butter.

## Skrifter

- Overskrifter: `--font-display` (Instrument Sans bold, stram spatiering). Serif kun i logoet.
- Alt andet: `--font-sans` (Instrument Sans 400/700). Ingen nye skrifter, intet fra Google Fonts.
- Display 56/60 -1.5px (mobil 40/44), H1 40/46 -1px, H2 28/34 -0.5px, H3 sans bold 20/26, brød 16/24, stor brød 18/28.

## Former

- Hjørner: 8px, 16px (kort), 28px (store flader), pill (knapper).
- Afstande kun 4, 8, 16, 24, 40, 64px (`--space-1` til `--space-6`).
- Ingen skygger, ingen gradienter, ingen grain, ingen blur.
- Signaturgrafik: enkle cirkler og prikker i grøn, Forest og Butter. Telefon- og browserrammer med streger i Ink/Line.
- Mobil først. Maks bredde 1120px.
- Animation kun transform og opacity, rolig og kort.

## Forbudt

Creme/beige/sand som baggrund. Terracotta og espressobrun. Store grønne flader. Pille-badges med farvet prik. Versal-etiket over hver overskrift. Fire forskelligfarvede kort side om side. Kæmpe falmet logo i footeren. Halvt mørk/halvt lys sektion med kort hen over. Pil i hvid cirkel på knapper. Tre korte slogan-sætninger i træk. Logoet genskabt som tekst.

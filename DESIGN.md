# Bama – design

Kort udgave til Impeccable. `../CLAUDE.md` og `brand/tokens.css` er de gældende regler. Er der uenighed, vinder de altid. Brug kun CSS-variablerne fra `tokens.css`, aldrig hårdkodede hex-værdier.

## Farver

| Token | Hex | Brug |
| --- | --- | --- |
| `--paper` | #FFFFFF | Sidebaggrund |
| `--surface` | #F4F6F3 | Kort, felter |
| `--tint` | #E7EBE5 | Afdæmpede sektioner, pladsholdere |
| `--line` | #D8DDD5 | Hårfine streger, kortrammer |
| `--ink` | #2A221D | Al tekst |
| `--ink-muted` | #5C5F59 | Sekundær tekst |
| `--clay` | #B5502C | Knapper og små accenter. Som tekst kun 24px+ |
| `--clay-deep` | #8E3B1E | Links, lille accenttekst, hover |
| `--forest` | #1F3A2F | Mørke flader (Om mig, abonnement, footer). Hvid tekst |
| `--butter` | #E7B547 | Ét fremhævet ord. Aldrig flader |

Fordeling ca. 70 % Paper/Surface/Tint, 15 % Ink, 10 % Forest, 5 % Clay/Butter.

## Skrifter

- Overskrifter: `--font-display` (Young Serif nu, Boston Angel senere).
- Alt andet: `--font-sans` (Instrument Sans 400/700). Ingen nye skrifter, intet fra Google Fonts.
- Display 56/60 (mobil 40/44), H1 40/46, H2 28/34, H3 sans bold 20/26, brød 16/24, stor brød 18/28.

## Former

- Hjørner: 8px, 16px (kort), 28px (store flader), pill (knapper).
- Afstande kun 4, 8, 16, 24, 40, 64px (`--space-1` til `--space-6`).
- Ingen skygger, ingen gradienter, ingen grain, ingen blur.
- Signaturgrafik: enkle cirkler og prikker i Clay, Forest og Butter. Telefon- og browserrammer med streger i Ink/Line.
- Mobil først. Maks bredde 1120px.
- Animation kun transform og opacity, rolig og kort.

## Forbudt

Creme/beige/sand som baggrund. Store Clay-flader. Pille-badges med farvet prik. Versal-etiket over hver overskrift. Fire forskelligfarvede kort side om side. Kæmpe falmet logo i footeren. Halvt mørk/halvt lys sektion med kort hen over. Pil i hvid cirkel på knapper. Tre korte slogan-sætninger i træk. Logoet genskabt som tekst.

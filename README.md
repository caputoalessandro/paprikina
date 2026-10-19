# Paprikina · Magyarul

Web app per imparare l'ungherese partendo dall'italiano, con Paprikina (una paprika) come mascotte.
30 unità in 6 gruppi: spiegazioni in italiano, lessico a blocchi, esercizi sulla regola e frasi miste, ripasso degli errori.
Funziona nel browser, si installa sulla schermata Home e funziona anche offline.

## Contenuto

| File | A cosa serve |
|---|---|
| `index.html` | L'app intera: contenuti, esercizi, grafica |
| `manifest.webmanifest` | Nome, colori e icona per l'installazione |
| `sw.js` | Funzionamento offline |
| `icon-*.png` | Icone di Paprikina |

## Pubblicare un aggiornamento

1. Sostituisci `index.html` con la nuova versione.
2. In `sw.js` cambia `VERSION` (per esempio da `paprikina-v1` a `paprikina-v2`).
3. Fai il commit: GitHub Pages aggiorna il sito in un paio di minuti.

## Pronuncia

L'app usa la voce ungherese del dispositivo.
- iPhone: Impostazioni → Accessibilità → Contenuto letto ad alta voce → Voci → Ungherese (Tünde).
- Android: Impostazioni → Sistema → Lingue → Sintesi vocale → motore Google → Magyar.

Gli esercizi sono originali; i libri di riferimento (MagyarOK, Hungarian: An Essential Grammar, Colloquial Hungarian, Complete Hungarian) sono stati usati per argomenti, lessico e verifica delle forme.
